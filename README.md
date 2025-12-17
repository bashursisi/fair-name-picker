# Fair Student Picker

A web application for teachers to fairly pick students for questions and generate lunch orders while keeping track of selection history.

## Features

- **Fair Question Selection**: Automatically prioritizes students who have been picked less frequently
- **Rotating Lunch Order**: Ensures students don't get stuck at the end of the line repeatedly
- **Persistent Data**: All statistics and history are saved automatically
- **Multi-Class Support**: Manages 8 different classes (5A-5F, 7A-7B)
- **Mobile-Friendly**: Optimized for use on iPhone and other mobile devices

## How to Use

1. Visit the live application: [Your GitHub Pages URL will go here]
2. Select your class from the buttons at the top
3. Choose a mode:
   - **Lunch Order**: Generate a randomized lunch line
   - **Pick for Questions**: Select a student fairly based on pick history
4. Click the button to perform the action
5. View statistics at the bottom to track fairness

## Data Persistence

All data is saved in your browser's localStorage:
- Student pick counts are tracked across sessions
- Lunch rotation history is remembered
- Statistics persist even when you close the browser
- Data is specific to each class

## Reset Statistics

Use the "Reset All Statistics" button at the bottom to start fresh at the beginning of a new term or school year.

## Classes

- 5A (24 students)
- 5B (23 students)
- 5C (13 students)
- 5D (24 students)
- 5E (24 students)
- 5F (24 students)
- 7A (empty - add students as needed)
- 7B (empty - add students as needed)

## Technical Details

This is a single-page HTML application using:
- Vanilla JavaScript (no frameworks required)
- localStorage for data persistence
- Responsive CSS design
- No server required - runs entirely in the browser

## License

Free to use for educational purposes.
