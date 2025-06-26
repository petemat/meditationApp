# Mindful Journey - 3D Meditation App

Welcome to Mindful Journey, a 3D meditation application designed to provide a serene and interactive space for mindfulness and relaxation. This project is built as a single-page web application using modern web technologies.

## Features

*   **Immersive 3D Scene:** A beautifully crafted island environment with a central meditating character, dynamic water, and a day/night cycle featuring a sun and moon.
*   **Interactive Camera:** The camera can be rotated around the character, snapping to four key perspectives, each offering a unique mindful prompt to guide the user's meditation.
*   **Customizable Meditation Sessions:**
    *   **Duration:** Choose from 5, 10, or 20-minute meditation sessions.
    *   **Ambient Sounds:** Unlockable soundscapes including 'Calm Waves', 'Rainfall', and 'Cosmic Hum'.
*   **User Progression System:**
    *   **Experience Points (XP) & Levels:** Gain XP by completing meditations to level up and earn new titles, from "Novice" to "Master".
    *   **Meditation Streak:** Tracks consecutive days of practice to encourage consistency.
    *   **7-Day Calendar:** Visualizes your meditation history for the past week.
*   **Character Selection:** Switch between two different 3D character models.
*   **Audio Controls:** Enjoy background music and ambient sounds, with a mute option for silence.
*   **Persistent Progress:** All user data, including level, XP, streak, and character choice, is saved locally in the browser.

## Technology Stack

*   **HTML5:** The core structure of the application.
*   **TailwindCSS:** For a utility-first approach to styling, enabling a responsive and modern UI.
*   **JavaScript (ES6+):** Powers all the application's logic and interactivity.
*   **Three.js:** A powerful 3D graphics library used to create and render the entire 3D scene.
*   **Tone.js:** For web audio, managing background music and generating ambient meditation sounds.

## How to Use

Since this is a single-file project, you can run it by simply opening the `index.html` file in a modern web browser that supports WebGL.

1.  Clone or download the repository.
2.  Navigate to the project directory.
3.  Open `index.html` in your browser (e.g., Chrome, Firefox, Safari, Edge).

## Project Structure

This project is intentionally contained within a single `index.html` file. This includes:

*   **HTML:** The structure and layout of the UI elements.
*   **CSS:** Inlined styles and TailwindCSS for the design.
*   **JavaScript:** All the application logic, including:
    *   3D scene setup and animation.
    *   UI event handling.
    *   Meditation and audio logic.
    *   User progress and data management.
