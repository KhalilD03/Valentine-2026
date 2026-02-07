HOW TO ADD YOUR VALENTINE'S FAVORITE SONG

Option 1: Rename your song to match the HTML
----------------------------------------
1. Rename your song file to "favorite_song.mp3" (or .m4a or .ogg)
2. Place it in this "music" folder
3. That's it! The HTML is already set up to use this filename

Option 2: Update the HTML to match your song name
----------------------------------------
1. Place your song file in this "music" folder (e.g., "our_song.mp3")
2. Open index.html in a text editor
3. Find the audio element (around line 250)
4. Update the src attribute to match your filename:
   <source src="music/our_song.mp3" type="audio/mpeg">

TIPS:
- Supported formats: MP3, M4A, OGG (most browsers support at least one)
- Avoid spaces in filenames (use underscores instead)
- Keep file size reasonable (under 10MB) for faster loading
- Test the website before showing it to your Valentine
- Music will start playing automatically as soon as the page loads
- Due to browser restrictions, the music will start muted and unmute on first interaction
- A music control button is visible from the start to pause/play the music
- For best results, open the page and click anywhere on it immediately
