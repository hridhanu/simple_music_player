
# 🎵 Simple Music Player 🎵

A feature-rich MP3 music player built with Python, leveraging Pygame for audio playback and Tkinter for the graphical user interface (GUI). This player allows users to load, play, pause, skip, and manage playlists with a user-friendly interface.


## 🚀 Features

- ✅ Play, Pause, Resume, Stop music
- ✅ Next & Previous Track navigation
- ✅ Volume Control with a slider
- ✅ Dynamic Playlist Management (load songs from a directory)
- ✅ MP3 Format Support (WAV & OGG can be added)
- ✅ Minimalistic GUI with Tkinter
- ✅ Persistent Playlist Storage (via pickle)




## 🛠 Installation

1️⃣ Install Python
Make sure you have Python 3.x installed.

2️⃣ Install Dependencies

Run the following command to install Pygame:

```bash
pip install pygame
```
3️⃣ Clone the Repository

```
git clone https://github.com/hridhanu/simple_music_player.git
cd simple_music_player
```
4️⃣ Run the Application
```
python music_player.py
```

    
## 📂 Project Structure

```
simple_music_player/
│── images/               # Contains button icons (play, pause, next, etc.)
│   ├── music.gif
│   ├── next.gif
│   ├── previous.gif
│   ├── play.gif
│   ├── pause.gif
│── music_player.py       # Main script for the music player
│── songs.pickle          # Stores the playlist (created dynamically)
│── README.md             # Project documentation

```
## 🎮 How to Use

- 1️⃣ Load Songs: Click the "Load Songs" button and select a directory containing MP3 files.
- 2️⃣ Play a Song: Double-click any song from the playlist to start playing.
- 3️⃣ Pause/Resume: Click the Pause button to pause playback and click again to resume.
- 4️⃣ Next & Previous: Navigate between tracks using the Next and Previous buttons.
- 5️⃣ Adjust Volume: Use the slider to control the playback volume.
## 🛠 Technologies Used

- Python – Core programming language
- Pygame – For audio playback
- Tkinter – For GUI components
- OS & Pickle – For playlist storage and file management
## 📌 To-Do List (Future Enhancements)

-  Add drag-and-drop song functionality
-  Support for more audio formats
-  Add shuffle & repeat mode
-  Improve UI with custom themes
## 🤝 Contributing

Feel free to fork this repository, improve it, and submit a pull request!
