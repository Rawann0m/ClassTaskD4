# ClassTaskD4
# Task 1
Overview

This is a simple user interface that includes:

A background with a purple overlay.

A horizontal stack (HStack) containing a profile image and a text label for the user’s name.

A button with an action that prints a message when tapped.

Features

ZStack for layering the background and UI elements.

VStack & HStack for proper layout structuring.

Custom Styling:

Profile image with resizing, padding, corner radius, and shadow.

Styled text label with bold font and white color.

Interactive button with a background color, corner radius, and tap action.
 # Task 2
 Overview
this app allows the user to enter their name, submit it, and see a greeting displayed on the screen. The app also features a toggle switch that changes the background color between blue and purple.

Features
Text Input: Users can enter their name in a TextField and click the "Submit" button to display a greeting.
Greeting: The name entered by the user is displayed with a personalized message after clicking the "Submit" button.
Background Color Toggle: A Toggle is provided to change the background color of the view between blue and purple.
Structure
ContentView: The main view contains a TextField for name input, a button to submit the name, a greeting message that updates dynamically, and a BackgroundToggleView that manages the background color change.
BackgroundToggleView: A separate view that holds the toggle switch, which binds to the ContentView to control the background color.
