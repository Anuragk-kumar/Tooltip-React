
# Tooltip React Component with Position Selection

This project demonstrates a simple React application that includes a customizable tooltip component. The tooltip's position can be adjusted using buttons to change its orientation (top, bottom, left, right) relative to a triggering element.



## Features

There are four buttons to control the position of the tooltip: Top, Bottom, Left, and Right.
The tooltip's visibility is toggled on hover over the triggering element.
The tooltip's appearance changes based on the selected position.

## Prerequisites

To run this project locally, you need the following:

Node.js installed on your machine
A code editor such as Visual Studio Code


## Deployment

Clone the repository or download the code files.


```bash
  git clone <repository_url>
```

Navigate to the project directory.

```bash
  cd <project_directory>
```

Install the required dependencies.


```bash
  npm install
```

Start the development server.

```bash
  npm start
```
Open your web browser and visit http://localhost:3000 to see the application in action.


## Project Structure

The project consists of two main files:

- Tooltip.js: This file contains the Tooltip component definition. It accepts a positioning prop to determine the tooltip's position and renders the tooltip element accordingly.
- App.js: This file contains the main App component definition. It includes the buttons to change the tooltip's position and renders the Tooltip component with the selected position.

## Styling

The project includes basic CSS styles to provide a visual structure to the application. The tooltip's appearance and position are styled using inline CSS based on the selected position.

## Notes
- The tooltip's visibility and opacity are controlled by the isVisible state variable using the useState hook.
- The tooltip's position is adjusted using the position prop passed to the Tooltip component.
- The tooltip's arrow orientation is determined by the selected position and is adjusted accordingly.
- The handleMouseEnter and handleMouseLeave functions toggle the isVisible state when hovering over the triggering element.
- The triggering element has the class hover and displays a dashed border for visual feedback.

Feel free to modify and expand upon this project as needed.



## Demo

Insert a GIF or link to the demo

