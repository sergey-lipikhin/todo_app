# Todo Application
[DEMO LINK](https://sergey-lipikhin.github.io/react-todo-app/)

Web application that allows users to create and manage a list of tasks. Users can add new tasks, mark them as completed, edit existing tasks, and delete tasks they no longer need. The application also includes a filtering system that allows users to view only completed or active tasks.

## Built with

- HTML: to create the structure and content
- CSS: to style and add animations
- React: the main frontend library to create the user interface and manage the application state
- TypeScript: to add static typing to the project and improve code maintainability
- fetchClient: to communicate with the [backend API](https://mate-academy.github.io/fe-students-api) and retrieve or update Todo items
- [React Transition Group](https://reactcommunity.org/react-transition-group/transition-group): to add smooth animations to the Todo list items when they are added or removed

## Features

- ➕ Add a new todo input a title in the input field and press Enter. Each new task will be given a unique ID.
- ✅ Mark as completed simply check the checkbox next to task. Conversely, uncheck the checkbox to mark it as not completed.
- ✎ Edit: double-click on a task to activate the edit mode, change title and then press Enter or click outside the field to save the changes.
- ✖️ Delete: click on the x button next to the task. Alternatively, make the title empty and save changes.
- 🔃 Filter todos: filter tasks by completion status by clicking on the All, Active, or Completed buttons.
- 🧹 Clear all completed todos: click on the Clear completed button.
- :eyes: View the total number of uncompleted tasks.

## Notification

If an error occurs while interacting with the API or due to an inappropriate user action, the corresponding notification message will be displayed at the bottom of the screen and then hidden after 3 seconds.
Possible error messages:
- An error occurred while loading todos
- Title can't be empty
- Unable to add a todo
- Unable to delete a todo
- Unable to delete one of these todos
- Unable to update a todo
