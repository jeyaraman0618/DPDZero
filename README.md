# DPDZero
Assignment
Part -1&2
Test Case 1: Loading the App
 Pre-conditions: The app is installed and launched successfully.
 Steps: Open the app.
    Expected Outcome: The app's main interface is displayed without any errors or crashes.

Test Case 2: Input Validation
Pre-conditions: The app is open and ready for user input.
 Steps: Try to add a task with an empty title.
    Expected Outcome: The app displays an error message indicating that the task title cannot be empty.

Test Case 3: Adding a Task
Pre-conditions: The app is open and ready for user input.
 Steps: Enter a valid task title.
        Press the "Add Task" button.
    Expected Outcome: The task is added to the list with the provided title, and it appears in the list of tasks.

Test Case 4: Marking a Task as Done
Pre-conditions: There is at least one task in the task list.
    Steps:
        Select an existing task from the list.
        Mark the task as done by clicking a "Mark as Done" button.
    Expected Outcome: The task is visually marked as done, and its status is updated accordingly.

Test Case 5: Deleting a Task
 Pre-conditions: There is at least one task in the task list.
    Steps:
        Select an existing task from the list.
        Delete the task by clicking a "Delete" button.
    Expected Outcome: The task is removed from the list and no longer appears in the app's interface.

Part -3
Test Case 1: Adding a Task

    Description: Verify that a task can be successfully added to the to-do list.
    Steps:
        Launch the app.
        Click on the "Add Task" button.
        Enter a task name and description.
        Click on the "Save" button.
    Expected Result: The task should be added to the to-do list. The task name and description should match the entered values.

Test Case 2: Viewing Task Details

    Description: Verify that task details can be viewed when clicking on a task in the to-do list.
    Steps:
        Launch the app.
        Click on a task in the to-do list.
    Expected Result: The app should display the task details, including its name and description.

Test Case 3: Marking Task as Completed

    Description: Verify that a task can be marked as completed.
    Steps:
        Launch the app.
        Add a task to the to-do list.
        Click on the checkbox or the "Mark as Completed" button next to the task.
    Expected Result: The task's status should change to "Completed" and it should be visually indicated as such.

Test Case 4: Editing Task

    Description: Verify that a task's details can be edited.
    Steps:
        Launch the app.
        Add a task to the to-do list.
        Click on the task to view its details.
        Click on the "Edit" button.
        Modify the task name and/or description.
        Click on the "Save" button.
    Expected Result: The task details should be updated with the new values provided during editing.

Test Case 5: Deleting Task

    Description: Verify that a task can be deleted from the to-do list.
    Steps:
        Launch the app.
        Add a task to the to-do list.
        Click on the task to view its details.
        Click on the "Delete" button.
    Expected Result: The task should be removed from the to-do list and no longer displayed.

Test Case 6: Marking All Tasks as Completed

    Description: Verify that all tasks in the to-do list can be marked as completed simultaneously.
    Steps:
        Launch the app.
        Add multiple tasks to the to-do list.
        Click on the "Mark All as Completed" button.
    Expected Result: All tasks should be marked as completed and visually indicated as such.

Test Case 7: Filtering Tasks

    Description: Verify that tasks can be filtered based on their completion status.
    Steps:
        Launch the app.
        Add both completed and incomplete tasks to the to-do list.
        Use the filtering options (e.g., "Show Completed," "Show Incomplete") to filter tasks.
    Expected Result: Only tasks matching the selected completion status should be displayed.

Test Case 8: Clearing Completed Tasks

    Description: Verify that completed tasks can be cleared from the to-do list.
    Steps:
        Launch the app.
        Add both completed and incomplete tasks to the to-do list.
        Click on the "Clear Completed" button.
    Expected Result: All completed tasks should be removed from the to-do list.

Test Case 9: Error Handling - Adding Task with Empty Name

    Description: Verify that the app handles the scenario when a user tries to add a task without a name.
    Steps:
        Launch the app.
        Click on the "Add Task" button.
        Leave the task name field empty.
        Enter a description.
        Click on the "Save" button.
    Expected Result: The app should display an error message indicating that a task name is required.

Test Case 10: Performance - Adding a Large Number of Tasks

    Description: Verify that the app can handle adding a large number of tasks without significant performance degradation.
    Steps:
        Launch the app.
        Add a large number of tasks to the to-do list (e.g., 100 tasks).
    Expected Result: The app should be able to add all the tasks without becoming unresponsive or excessively slow.


