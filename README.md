# Songsay-Music-Sharing-Page-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Songsay Artist Signup</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Join Songsay: Empower Your Music Sharing Experience</h1>
            <p>Welcome to Songsay, where artists like you can create a dedicated music-sharing page to connect with fans like never before. Fill out the form below to get started and take your music to the next level!</p>
        </header>
        <form id="signup-form">
            <div class="form-group">
                <label for="artist-name">Artist Name:</label>
                <input type="text" id="artist-name" name="artist-name" required>
            </div>
            <div class="form-group">
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number (with country code):</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="instagram">Instagram Link:</label>
                <input type="url" id="instagram" name="instagram" required>
            </div>
            <div class="form-group">
                <label for="tiktok">TikTok Link:</label>
                <input type="url" id="tiktok" name="tiktok" required>
            </div>
            <div class="form-group">
                <label for="twitter">X (Twitter) Link:</label>
                <input type="url" id="twitter" name="twitter" required>
            </div>
            <div class="form-group">
                <label for="spotify-artist">Spotify Artist Link:</label>
                <input type="url" id="spotify-artist" name="spotify-artist" required>
            </div>
            <div class="form-group">
                <label for="youtube-channel">YouTube Channel Link:</label>
                <input type="url" id="youtube-channel" name="youtube-channel" required>
            </div>
            <div class="form-group">
                <label for="spotify-tracks">Links for Spotify Tracks:</label>
                <textarea id="spotify-tracks" name="spotify-tracks" required></textarea>
            </div>
            <div class="form-group">
                <label for="youtube-videos">Links for Videos on YouTube:</label>
                <textarea id="youtube-videos" name="youtube-videos" required></textarea>
            </div>
            <div class="form-group">
                <label for="lyrics">Lyrics files:</label>
                <input type="file" id="lyrics" name="lyrics" required>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>
    <footer>
        <p>For any questions or support, please contact us at <a href="mailto:support@songsay.com">support@songsay.com</a>.</p>
        <p>Follow us on <a href="#">Instagram</a>, <a href="#">TikTok</a>, <a href="#">Twitter</a>, and <a href="#">YouTube</a> for the latest updates and artist features!</p>
        <p><a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
