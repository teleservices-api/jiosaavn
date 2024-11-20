# JioSaavn Telegram Bot

A Python Telegram bot leveraging the Pyrofork library to search and upload songs, albums, playlists, and artists from JioSaavn. This bot utilizes hidden APIs from JioSaavn to provide a seamless music experience on Telegram.

[![GitHub](https://badgen.net/badge/Open%20Source%20%3F/Yes/yellow?icon=github)](https://github.com/teleservices-api/jiosaavn)


## Features

- **Search** for songs, albums, playlists, and artists on JioSaavn.
- **Upload** songs directly to Telegram.
- Supports multiple search types (songs, albums, playlists, artists).

## Usage

1. **Start the Bot**: Send the `/start` command.
2. **Search**: Send a query to search for a song, album, playlist, or artist.
3. **Select**: Choose the desired result from the search list.
4. **Upload**: Select the upload option to upload the song to Telegram.

## Commands

- `/start` - Initialize the bot and check its status.
- `/settings` - Configure and manage bot settings.
- `/help` - Get information on how to use the bot.
- `/about` - Learn more about the bot and its features.

## Installation

1. **Clone the Repository**: 
   ```sh
   git clone https://github.com/teleservices-api/jiosaavn.git
   ```
2. **Install Dependencies**:
   ```sh
   pip3 install -r requirements.txt
   ```
3. **Run the Bot**:
   ```sh
   python3 -m jiosaavn
   ```

## Running Methods

1. **Deploy to Koyeb**:
    [![](https://img.shields.io/badge/Click_here-blue)](https://github.com/teleservices-api/jiosaavn#features)

2. **Local Setup**:
   - Ensure you have Python and pip installed.
   - Follow the Installation steps above.

## Dependencies

- [Pyrofork](https://pyrofork.mayuri.my.id/main/)
- Custom JioSaavn API

## How to Deploy

1. Click the **Deploy to Koyeb** button below.
2. On the Koyeb UI, you'll be asked to fill in the environment variables.

   The required environment variables are:
   - `DATABASE_URL`: Your database connection URL.
   - `BOT_TOKEN`: Your bot token for Telegram API.
   - `API_HASH`: Your API hash for the Telegram API.
   - `API_ID`: Your API ID for the Telegram API.

3. Once the environment variables are set, click **Deploy** to deploy the application.

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&builder=buildpack&repository=https://github.com/teleservices-api/jiosaavn&branch=main&name=jiosaavn-api&run_command=python3%20-m%20jiosaavn)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.


## Credit 

[Ns-AnoNymouS](https://github.com/Ns-AnoNymouS) For His Amazing Repo
