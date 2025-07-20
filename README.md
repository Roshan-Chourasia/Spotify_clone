<h1>Spotify Clone</h1>

A web-based Spotify clone built with HTML, CSS, and JavaScript. This project mimics the core features of Spotify’s web player, letting users browse playlists, view albums, and play music right in the browser.


**Features:**

🎵 Modern Spotify-like UI: Responsive, visually appealing, inspired by Spotify.

📁 Dynamic Playlists: Albums and playlists are loaded dynamically from the songs directory.

🖼️ Album Covers & Metadata: Each album shows a cover image and description.

▶️ Music Player: Play, pause, skip, previous, and seek functionality.

🔊 Volume Control & Mute: Adjust or mute the volume.

📱 Responsive Design: Optimized for both desktop and mobile devices.


**How to Use:**

1. Clone or Download the Repository:
git clone - https://github.com/Roshan-Chourasia/Spotify_clone.git

2. Add Your Songs:
   
- Navigate to the songs folder.
- Each subfolder represents an album or playlist (for example, Bollywood, Arijit_singh).
- To add your own album or playlist:
  1. Create a new folder inside songs/ (for example, MyAlbum).
  2. Add a cover.jpg (album cover image).
  3. Add an info.json file with the following:
     {
      "title": "My Album Title",
      "description": "A short description of the album"
     }
  4.Place your .mp3 files inside this folder.

**Note:** The app will automatically detect and display any new albums/playlists you add. Just refresh the page to see your new music!

3. Run the Project

- Open index.html in your web browser.
- No server setup is required for basic usage. For full functionality (like fetching local files), use a local server, such as: VSCode Live Server, Python: python -m http.server, Node: npx http-server.

4. Browse and Play

- Click on any album to view its songs.
- Click a song to play it.
- Use the player controls at the bottom to play/pause, skip, seek, and adjust volume.

**Screenshot:**

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d9da532b-e36f-493f-a631-c3044b9efb85" />

**Customization:**

Styling:
Edit css/style.css and css/utility.css to change the look and feel.

Icons/Images:
Replace or add icons in the img/ folder as needed.

**Credits:**
- UI inspired by Spotify
- Icons from SVGRepo and similar sources
- Developed by Roshan Chourasia

**License:**
This project is for educational purposes only and is not affiliated with or endorsed by Spotify.
