 # Music Player Application

This project is a simple, interactive web-based music player built using **HTML**, **CSS**, and **JavaScript**. It allows users to play a single audio track, control playback, and seek through the song using a progress bar.


## Features

### 1. **Play/Pause Functionality**
- Users can toggle between playing and pausing a song by clicking the play/pause button.

### 2. **Progress Bar**
- Displays the current playback progress.
- Allows users to seek through the song by dragging the progress bar.

### 3. **Dynamic Song Info**
- Displays the song title and artist.

### 4. **Automatic Play Pause Toggle**
- Automatically updates the play/pause button icon based on the current state of the audio.

## How to Run the Project

1. Clone or download the project files.
2. Ensure the audio file and image are placed in the appropriate `Media` folder.
3. Open `index.html` in a web browser to launch the music player.

## File Structure

```
Music Player Application
├── index.html           # Main HTML file
├── style.css            # CSS file for styling
└── Media/               # Folder containing audio file and image
    ├── song.mp3
    └── song-image.jpeg
```

## JavaScript Functions

### `playPause()`
Toggles between playing and pausing the current song and updates the play/pause button icon accordingly.

### Event Listeners
- **`song.onloadedmetadata`**: Initializes the progress bar's max value when the song's metadata is loaded.
- **`song.ontimeupdate`**: Updates the progress bar as the song plays.
- **`progress.oninput`**: Allows users to seek through the song.


## Technologies Used

- **HTML5** for the structure.
- **CSS3** for styling.
- **JavaScript (ES6)** for interactivity and functionality.


## Author
**Sudhanshu Ranjan Patra**

Feel free to contribute to this project or suggest enhancements!


