# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* onClick - dispatches the addOne function in our action
* Return Action Object - returns the action type ADD_ONE
* Enter Reducer - finds the ADD_ONE case related to the action type
* Returns the ADD_ONE case's functionality
* Rerenders Application
* TotalDisplay shows the total plus 1.
