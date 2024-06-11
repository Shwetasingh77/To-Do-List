# Getting Started with Create React App
# React To-Do List

# Description
This project is a React To-Do List component that allows users to manage tasks by adding, editing, removing, and marking them as completed. It also offers filtering options to view all tasks, active tasks, or completed tasks. The component integrates with localStorage for data persistence, ensuring tasks remain saved between sessions.

#Features
Add new tasks
Edit existing tasks
Remove tasks
Mark tasks as completed
Filter tasks by completion status (all, active, completed)
Integration with localStorage for data persistence
Modern and clean design with a dark theme
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/Shwetasingh77/To-Do-List.git
Install dependencies:

Copy code
npm install
Run the development server:

sql
Copy code
npm start
Access the application in your web browser at https://extraordinary-pithivier-9bed51.netlify.app/.

Testing Guidance
Adding Tasks: Enter text in the input field and click "Add Task" button. Verify the task is displayed correctly in the list.

Editing Tasks: Click the edit button next to a task, modify the text, and save the changes. Confirm the task text updates accordingly.

Removing Tasks: Click the delete button next to a task. Ensure the task is removed from the list.

Marking Tasks as Completed: Click the checkbox button next to a task. Check that the task is visually marked as completed with a line-through.

Filtering Tasks: Click the filter buttons (All, Active, Completed). Verify tasks are displayed according to the selected filter.

LocalStorage Integration: Add tasks, refresh the page, and verify tasks remain in the list.

Styling and Layout: Test the overall styling and layout for readability and usability.

Cross-browser Compatibility: Ensure the component functions correctly across different web browsers.

Feedback and Bug Reporting: Provide feedback and report any bugs or issues encountered during testing.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [https://extraordinary-pithivier-9bed51.netlify.app/](https://extraordinary-pithivier-9bed51.netlify.app/) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

