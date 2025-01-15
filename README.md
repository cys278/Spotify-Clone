## Spotify-Clone

This project is a clone of the Spotify web player, providing a seamless interface for music streaming and album browsing. Built using HTML, CSS, and JavaScript, this project mimics the functionality and design of Spotify’s web player. Users can browse albums, view playlists, and play music with essential playback controls.

Features

**1. User Interface**

Left Panel Navigation:

a) Displays the logo, home button, search button, and a library section.

b) Includes legal and accessibility links in the footer.

Right Panel Content:

a) Displays albums with cover images, titles, and descriptions.

b) Includes a sticky playbar with playback controls at the bottom.


2. Music Playback

a) Play, pause, next, and previous song functionalities.

b) Dynamic seek bar for precise control of the playback position.

c) Displays song information including title and duration.

d) Volume control with mute/unmute functionality.


3. Dynamic Content Loading

a) Fetches songs and albums dynamically using the Fetch API.

b) Metadata of albums (e.g., title and description) is retrieved from JSON files in the respective album folders.

c) Automatically populates songs in the playlist section when an album is selected.

4. Responsive Design

a) Fully responsive layout for desktop and mobile devices using CSS Media Queries.

b) Hamburger menu for navigation on smaller screens.

5. Custom Styling

a) Dark-themed UI with custom scrollbars.

b) Hover effects on cards and buttons for better interactivity.

c) Reusable utility classes for consistent styling.





Technologies Used

Frontend

1. HTML:

Structured the layout of the application.

2. CSS:

a) Styled the application, including a responsive design using CSS Media Queries.

b) External fonts from Google Fonts.

c) Utility classes for margins, padding, and flexbox properties.

d) Custom scrollbars for better user experience.

3. JavaScript

a) Used ES6+ features like async/await, forEach, and template literals.

b) Modularized functionalities:

c) Fetching and displaying albums dynamically.

d) Attaching event listeners for play/pause, volume, and navigation controls.

Manipulated the DOM dynamically for updating UI components such as the seek bar and song info.

4. APIs and Tools

a) Fetch API for retrieving album metadata and song lists.

b) Local JSON files for album metadata.




Code Features

1.Utility Functions

a) secondsToMinutesSeconds(seconds): Converts seconds into a MM:SS format.

b) Dynamic Fetching

2. Albums:

a) Fetched from the songs folder dynamically.

b) Metadata (e.g., title and description) fetched from info.json in each album folder.

3. Songs:

a) Fetched based on the selected album.

b) Displays in a playlist section with dynamic event listeners for playback.

4. Event Handling

a) Playback Controls: Play, pause, next, and previous buttons. Seek bar for controlling the current position in the song.

b) Volume Control: Range input for adjusting volume. Mute/unmute toggle.

c) Responsive Navigation: Hamburger menu for opening and closing the left panel on smaller screens.

5. Responsiveness: Designed using media queries to ensure adaptability across devices. Custom styling for the playbar and playlist on mobile screens.




How to Run the Project

1) Clone the repository to your local machine.

2) Open the index.html file in any modern web browser.

3) Ensure that the project folder structure includes:

index.html: Main HTML file.

style.css: Main CSS file.

utility.css: Utility classes for consistent styling.

script.js: Main JavaScript file.

songs/: Folder containing album subfolders with cover.jpg and info.json.

Required SVG files for icons (e.g., play.svg, pause.svg).

Use a local server (e.g., Live Server) to enable dynamic fetching for JSON and music files.



This project was designed and implemented by **Chowdhury Yasir** as a personal project to learn and showcase frontend development skills.




