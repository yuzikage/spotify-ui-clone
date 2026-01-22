# Spotify Clone - Web Player UI

A visually accurate clone of the **Spotify Web Player** interface. This project focuses on replicating a complex dashboard layout using pure HTML and CSS, featuring a multi-pane design, a sticky navigation bar, and a functional-looking music player control bar.

## 🌟 Features

* **Complex Layout:** Three-pane design featuring a fixed sidebar, scrollable main content, and a fixed bottom music player.
* **Sticky Navigation:** Top navigation bar that remains visible while scrolling through music categories.
* **Custom UI Components:** * **Music Player:** Includes album art, song info, play/pause controls, and custom-styled progress bars.
    * **Sidebar Library:** "Glassmorphism" boxes for playlist and podcast prompts.
    * **Responsive Cards:** Grid-based layout for albums and playlists that wrap based on screen size.
* **Custom Styling:** Customized `-webkit-slider` tracks for the volume and progress bars to match the Spotify "Green" aesthetic.
* **Responsiveness:** Uses media queries to hide specific elements (like "Premium" buttons) on smaller viewports.

## 🛠️ Built With

* **HTML5:** Semantic structure for different sections (Sidebar, Main, Player).
* **CSS3:** Flexbox for layout, fixed/sticky positioning, and custom transitions.
* **Font Awesome:** For all UI icons (Home, Search, Library, Player Controls).
* **Google Fonts:** "Montserrat" for that classic Spotify typography.

## 📂 Project Structure

* `index.html` - The structural markup for the sidebar, content grid, and player.
* `style.css` - Comprehensive styles including custom scrollbars, hover states, and the playback bar UI.
* `assets/` - Contains icons and card images for the music categories.
* `homework assets/` - Contains specific assets for the album and player controls.

## 🚀 Getting Started

### Installation
1.  Clone the repository:
    ```bash
    git clone https://github.com/yuzikage/spotify-ui-clone.git
    ```
2.  **Asset Setup:** Ensure the `./assets/` and `./homework assets/` folders are present with the required images, or replace the `src` paths in the HTML with your own music images.

### Usage
Open `index.html` in any modern browser. 
* **Scroll** through the main content to see the sticky header in action.
* **Hover** over cards and buttons to see the opacity and scale transitions.
* **Interact** with the progress and volume sliders.

---
*Created with 🎵 by [Smit](https://github.com/yuzikage)*
