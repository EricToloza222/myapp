# Project Blueprint

## Overview

This is a simple Flutter counter application. The user can increment a counter, and when the counter reaches 10, the user can reset it.

## Features

*   **Counter:** A simple counter that starts at 0.
*   **Increment Button:** A floating action button that increments the counter by 1.
*   **Reset Button:** When the counter reaches 10, the increment button is replaced by a reset button that sets the counter back to 0.
*   **Color Change:** When the counter reaches 10, the number turns red.

## Current Request

The user wants to add a button to reset the counter when it reaches 10. When the counter is 10 or more, the increment button should be hidden, and a red "Reiniciar" button should be shown. When the "Reiniciar" button is pressed, the counter should be reset to 0.

### Plan

1.  Read the `lib/main.dart` file.
2.  Modify the `_incrementCounter` function to check if the counter is 10 or more.
3.  Add a `_resetCounter` function to set the counter back to 0.
4.  In the `build` method:
    *   Change the color of the counter text to red if the counter is 10 or more.
    *   Conditionally show the increment button or the reset button based on the counter's value.
5.  Write the updated code to `lib/main.dart`.
6.  Create a `blueprint.md` file to document the project and the current changes.
7.  Inform the user that the changes have been made.
