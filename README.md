# Color Switcher

This simple web application allows you to dynamically change the background color of the page. You can start and stop the color-switching process using the "Start" and "Stop" buttons.

## Features

- **Start Button:** Initiates the color-switching process. The background color changes every second.
- **Stop Button:** Halts the color-switching process.
- **Go Back Button:** This button is not present in the original code but has been added for convenience. It allows you to navigate back to the previous page.

## Implementation

- The `getRandomHexColor` function generates a random hex color code.
- The `changeBackgroundColor` function sets the background color of the body to a randomly generated color.
- The `startButton` initiates the color-switching process by setting up an interval that calls `changeBackgroundColor` every second.
- The `stopButton` stops the color-switching process by clearing the interval and resetting the background color to its current state.
- The `goBack` function is added for convenience, allowing you to navigate back to the previous page.

## Usage

1. Open the HTML file in a web browser.
2. Click the "Start" button to begin the color-switching process.
3. Click the "Stop" button to halt the color-switching process.
4. Optionally, use the "Go Back" button to navigate to the previous page.

Feel free to customize and enhance the application as needed!
