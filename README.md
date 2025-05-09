# Tapestry Automa Tracker

A simple, single-page web application to help track the state of the Automa player when playing the board game Tapestry solo or cooperatively. This tracker helps manage Automa's position on the advancement tracks, resources, buildings, claimed landmarks, and turn history.

## Features

* **Track Automa & Player Positions:** Visually track the current space for both the Automa and the Human player on all five advancement tracks (Exploration, Technology, Science, Military, Arts).
* **Automa Logic Simulation:** Simulates the Automa's turn based on its character (Normal or Strategic) and the priority rules, including tiebreakers.
* **Resource & Building Tracking:** Keep track of Automa's current resource count and the number of each income building (Market, Farm, House, Armory) it possesses.
* **Landmark Status:** Track the status of all landmarks (Available, Claimed by Player, Claimed by Automa, or Gone).
* **Turn History:** Maintains a history of Automa and Player actions for review.
* **Undo/Redo:** Easily correct mistakes or explore different moves with undo and redo functionality.
* **Manual Adjustments:** Manually adjust Automa's resources, buildings, and both player/automa positions if needed.
* **Persistent State:** The game state is automatically saved to your browser's local storage, so you won't lose your progress if you refresh the page or close and reopen the browser.
* **Responsive Design:** Designed to be usable on various screen sizes.

## Automa Characters Supported

* Normal
* Strategic

## How to Use

This application is a single HTML file.

1.  Save the provided code as an HTML file (e.g., `index.html`).
2.  Open the `index.html` file in your web browser.
3.  Follow the on-screen setup to select the Automa's color and character.
4.  Use the "Automa Turn" button to have the Automa take its turn.
5.  Click on track spaces to manually advance your player's position.
6.  Use the adjustment buttons to modify Automa's state or player/automa positions as needed.
7.  The state is automatically saved to your browser's local storage.

## Technologies Used

* HTML
* CSS (using Tailwind CSS CDN)
* JavaScript (using React via CDN)

## Contributing

As this is a simple, single-file project, direct contributions via pull requests might be complex. However, feel free to open issues for bug reports or feature suggestions.

## License

This project is open source and available under the [MIT License](LICENSE) (You might want to create a LICENSE file if you plan to distribute this).
