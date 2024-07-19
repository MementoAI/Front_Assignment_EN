# Front-end development challenge

This project challenges you to configure your own Webpack settings and implement a drag-and-drop functionality that works according to the given requirements. Using the `react-beautiful-dnd` library, you should create an application that satisfies the specified dragging constraints. Starting from an initial file with the minimum functionality provided, you should fulfill the following tasks.

## Assignment Objective.

- **Apply Webpack**: Configure a React application by setting up Webpack directly, without using `react-scripts`.
- Expand the columns: Expand the existing one column to four columns.
- Apply drag constraints: Restrict the dragging of items based on specific rules.
- Implement multi-drag functionality: Add the ability to select and drag multiple items at the same time.

### 1. Applying Webpack

For this assignment, you will need to implement the Webpack setup yourself instead of the `react-scripts` in `create-react-app`. Set up the initial `index.js` file and `webpack.config.js` file so that you can build the React application.

### 2. Expand the columns

Currently, the application has only one column. We need to expand it to four columns and each column should have an independent drag and drop area.

### 3. Drag constraints

- It should not be possible to move an item from the first column to the third column.
- An even item cannot be moved in front of another even item.
- If an item is dragged to a point where it cannot be moved, make sure the user is aware of the constraint.
  (e.g., the color of the item being dragged changes to red, etc.)

### 4. Implement multi-dragging

The user should be able to select multiple items and drag them together to move them to different columns.

## Development Guidelines

- Design a user-friendly interface with UX in mind (you may add UI and features outside of the assignment goals to accomplish this).
- Except for #1, you may not use any libraries other than `react-beautiful-dnd` for the assignment.
- However, you may use your favorite styles (CSS-in-JS, tailwind, etc.)

## How to submit

Upload your finished project code to a Git repository and submit a link to that repository.

### Evaluation criteria

- Correctness of Webpack configuration
- Correct implementation of drag and drop functionality
- Readability and structuring of the code
- User experience and interface design

Translated with DeepL.com (free version)
