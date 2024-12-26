# BlacklistBot

A Discord bot that helps manage blacklists using Google Drive integration and database functionality.

## Features

- Discord server integration
- Google Drive file management
- Database support for persistent storage
- Guild (server) configuration management
- Extensible architecture with support for custom extensions

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/blacklistbot.git
cd blacklistbot
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your credentials:
   - Place your Discord bot token in the appropriate location in the `credentials` directory
   - Set up Google Drive API credentials and save the `token.pickle` file

## Configuration

The bot uses `guilds.json` for server-specific configurations. Each guild can have its own settings and preferences.

## Project Structure

- `app.py` - Main bot application entry point
- `database.py` - Database interaction layer
- `drive.py` - Google Drive integration
- `extensions/` - Bot command extensions
- `utils/` - Helper utilities
- `credentials/` - Directory for storing sensitive credentials
- `guilds.json` - Server configuration file

## Usage

To start the bot:

```bash
python app.py
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Add your license information here]