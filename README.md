# Day_28-Pomodoro-app-project
A Pomodoro Timer App built using Python’s tkinter library
The Pomodoro Technique is a time management method where you Work for 25 minutes, Take a short break (5 minutes), After several cycles, take a longer break (15–20 minutes)

This app automates that cycle, helping users stay focused and productive with a visual timer and progress tracking.

## How the code works:
- A GUI window is created using tkinter with a clean layout and color theme
- A canvas widget is used to display a tomato image (representing the Pomodoro technique 🍅) and show the countdown timer text
- When the user clicks 'Start', the app begins a countdown (work session first)
    It alternates between:
    Work sessions
    Short breaks
    Long breaks after multiple cycles
- The timer updates every second using window.after() (no freezing UI!)
- A Reset button allows the user to restart the timer
- Progress is tracked using checkmarks (✔), showing completed work sessions

## What I learned:
- Working with the Canvas widget:
    Creating a canvas in Tkinter
    Adding images using PhotoImage
    Overlaying text on images
- Building a dynamic timer⏱️
- Using window.after() to schedule repeated actions
- Creating a real-time countdown mechanism
- Tracking repetitions to control work/break cycles
- Using global variables effectively
- Using conditional logic for different timer phases
- Improving UI design🎨:
    Using colors, fonts, and layout to enhance user experience
- Structuring the interface with grid()
- Buttons triggering functions (Start, Reset)
- Updating UI elements dynamically

This project brought together everything learned about Tkinter and event-driven programming to build a fully functional productivity tool.
