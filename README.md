# MauiTouchIssues

This is a sample ASP.NET Blazor application implementing a simple counter functionality. Furthermore, this page includes multiple input fields, which may be tested to understand touch-related usability or performance issues in mobile environments. This is intended to show the issues in MAUI Blazor with switching from using touch screen to the mouse / touch-pad.

## Project Overview

- **Framework**: .NET 8.0
- **UI Technology**: Blazor (MAUI Blazor Project)

### Features

1. A counter button that increments the count upon each click.
2. A series of input boxes to simulate field-heavy UI scenarios.

## File Contents

The `Counter.razor` page contains:
- A counter with a button labeled `Click me`.
- A series of 20+ input fields for testing input-related interactions.

## How to Run the Application

1. Clone this repository locally.
2. Ensure you have the required .NET SDK installed (at least .NET 8.0).

## Instructions to Test for Touch Issues

The following steps will help you reproduce any potential touch-related issues:

1. **Launch the Application**:
   - Run the application on an **Windows App**.

2. **Navigate to Counter Page**:
   - Verify that the page renders properly, showing the counter, button, and a series of input fields.

3. **Test Button Touch Interaction**:
   - Tap the `Click me` button multiple times.
   - Observe if the `Current count` value increments correctly.

4. **Input Field Testing**:
   - Tap each of the text input fields.
   - Type different values and navigate between the fields.
   - Check for any performance lag or difficulty in selecting specific fields using touch.

5. **Multiple Field Scrolling**:
   - Scroll through the page by dragging up and down across the input fields.
   - Observe if the scrolling gesture works as expected, or if the app encounters touch sensitivity issues.

6. **Other Gesture Interactions**:
   - Attempt multi-touch gestures like pinch-to-zoom or interaction with multiple input fields rapidly.
   - Document any unexpected behavior.
