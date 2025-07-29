🔑 React Password Generator
A simple and clean password generator application built with React and Vite. This project was created as a hands-on exercise to deepen my understanding of core React concepts, particularly Hooks like useState, useCallback, useRef, and useEffect.

You can replace the placeholder above with a screenshot of your application.

✨ Features
Customizable Password Length: Generate passwords with a length ranging from 8 to 100 characters using a slider.

Character Set Options: Easily toggle the inclusion of numbers (0-9) and special characters (!@#$%^&* etc.).

One-Click Copy: A convenient button to instantly copy the generated password to the clipboard.

Real-time Regeneration: The password automatically updates whenever the generation criteria (length, character sets) are changed.

Clean & Responsive UI: A modern and simple interface that works well on all screen sizes.

🚀 Tech Stack & Learning Highlights
This project is built with modern frontend technologies and focuses on the practical application of React's powerful Hook system.

Framework: React

Build Tool: Vite

Styling:  Tailwind CSS 

Core Concepts Practiced
The main goal of this project was to learn and implement the following React Hooks:

useState: Used to manage all stateful logic, including:

The generated password string.

The password length value from the slider.

The boolean state for the "Include Numbers" and "Include Characters" checkboxes.

useCallback: Applied to memoize the main password generation function. This ensures that the function is not recreated on every component re-render, optimizing performance. It's only recomputed when its dependencies (the character set options) change.

useEffect: Used to trigger the password generation logic whenever the user modifies any of the password criteria (length, number inclusion, or character inclusion). This creates a reactive experience where the password updates automatically.

useRef: Implemented to create a reference to the password input field. This reference is essential for the "copy to clipboard" functionality, allowing direct interaction with the DOM element to select its content.
