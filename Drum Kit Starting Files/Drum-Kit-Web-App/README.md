# Drum Kit Web App


This project is a simple interactive Drum Kit web application built using HTML, CSS, and JavaScript. The app allows users to play drum sounds by either clicking on drum buttons on the screen or pressing specific keys on the keyboard.

Features:
Button Click Detection: Each drum button on the screen is associated with a specific drum sound. When the user clicks on a button, the corresponding sound is played.
Key Press Detection: The app also listens for keypress events, so users can play drum sounds by pressing the keys "w", "a", "s", "d", "j", "k", and "l" on their keyboard.
Audio Playback: The app uses the Audio object in JavaScript to load and play different drum sounds based on user interaction.
Responsive Design: The drum kit layout is responsive and adjusts to different screen sizes.
How it Works:
Event Listeners: The app adds event listeners to all drum buttons to detect mouse clicks and to the entire document to detect keyboard presses.
Sound Mapping: Each button and key is mapped to a specific drum sound (e.g., "w" plays tom-1.mp3, "a" plays tom-2.mp3, etc.).
Audio Control: When an event is detected, the corresponding sound file is loaded and played using the audio.play() method.
This project is a great example of how to handle user interactions and dynamic audio playback in a web application.
