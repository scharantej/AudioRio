## Design for a Music Streaming Service using Flask

### HTML Files

**1. index.html**

- Landing page of the application.
- Contains login/signup form and links to browse music.

**2. browse.html**

- Displays a list of available music categories and artists.
- Allows users to filter and search for specific music.

**3. player.html**

- Music playback page.
- Contains music player controls, playlist, and song lyrics (if available).

### Routes

**1. /login**

- Route for user login.
- Validates user credentials and creates a session if successful.

**2. /signup**

- Route for user signup.
- Creates a new user account and handles password hashing.

**3. /browse**

- Route for browsing music.
- Displays a list of music categories and artists based on query parameters.

**4. /play**

- Route for playing music.
- Accepts a song ID as a parameter and streams the song to the client.

**5. /add_to_playlist**

- Route for adding a song to the user's playlist.
- Accepts a song ID and playlist ID as parameters.

**6. /create_playlist**

- Route for creating a new playlist.
- Accepts a playlist name as a parameter.

**7. /get_lyrics**

- Route for fetching lyrics for a song.
- Accepts a song ID as a parameter.