# Discord Music Bot 🎵

A simple Discord music bot built with Python and `yt-dlp`, allowing users to play music from YouTube directly in their Discord voice channels. The bot includes basic features like playing songs, skipping tracks, and managing a song queue.

## Basic Features

- **Play Music**: Play songs from YouTube by searching or providing a direct link.
- **Skip Tracks**: Skip the current track to play the next one in the queue.

## Getting Started

### Prerequisites

Make sure you have the following installed:
<img align="right" width=200px src="https://media1.tenor.com/m/TlgUEqfuG4gAAAAd/spinning-music.gif" />

- Python 3.8 or higher
- `discord.py` library
- `yt-dlp` library
- `ffmpeg` (for audio processing)

### Installation,

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/discord-music-bot.git
   cd discord-music-bot
   ```

2. **Install dependencies**:
   Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
   Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup your Discord bot**:
   - Create a bot on the [Discord Developer Portal](https://discord.com/developers/applications).
   - Get your bot token and replace `'YOUR_BOT_TOKEN'` in the code.

4. **Run the bot**:
   ```bash
   python bot.py #(bot = your file name)
   ```

### Usage

1. **Invite the bot to your server**:
   - Generate an OAuth2 URL with the `bot` scope and `administrator or Connect and Speak` permissions from the Developer Portal and use it to invite the bot to your Discord server.
   - Must need Connect and Speak permissions
    
2. **Bot Commands**:
   - `!play <song name or URL>`: Play a song or add it to the queue.
   - `!skip`: Skip the currently playing song.

### Example

- `!play never gonna give you up`: Searches YouTube for the song and plays it in the voice channel.
- `!skip`: Skips to the next song in the queue.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure your code follows the existing style and structure.

## Acknowledgements

- [discord.py](https://github.com/Rapptz/discord.py) - The Python API wrapper for Discord.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - A command-line program to download videos from YouTube and other video sites.
- [FFmpeg](https://ffmpeg.org/) - A complete, cross-platform solution to record, convert and stream audio and video.


## License

This project is licensed under me [LICENSE](https://github.com/Nuwan-Srimal), 
<br>
Contact for more details, Click me.
<a href="https://discord.gg/https://discord.gg/edEe8tr42D" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="https://discord.gg/edEe8tr42D" height="50" width="40" /></a>


