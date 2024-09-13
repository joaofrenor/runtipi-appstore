# Torrent Indexer

Torrent Indexer is a powerful tool for searching and indexing torrent files. This service provides a user-friendly interface to search for torrents across various sources, making it easier to find and manage digital content. With its efficient indexing system, Torrent Indexer offers fast search results and up-to-date information on available torrents.

## Key Features

- Fast and efficient torrent searching
- User-friendly interface
- Regularly updated torrent database
- Integration with Redis for improved performance

## Usage

The Torrent Indexer service runs on port 7006 by default. You can access the web interface by navigating to `http://your-server-ip:7006` in your web browser.

## Note

This tool is for informational purposes only. Users are responsible for complying with all applicable laws and regulations regarding the download and use of copyrighted material.

## Technical Details

- The app uses Redis for caching and improved performance.
- The main service runs on port 7006.
- Both the indexer and Redis services are part of the `indexer` network for internal communication.

For more information and updates, visit the [GitHub repository](https://github.com/felipemarinho97/torrent-indexer).