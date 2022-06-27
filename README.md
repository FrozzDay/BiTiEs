<h1 align="center">NOTFLIX</h1>
Notflix is a shell script to search and stream torrent. from <a href="https://github.com/Bugswriter/notflix">Bugswriter</a>

### How does this work?

This is a shell script. It scrape 1337x and TPB to get the magnet link.
It uses [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Execute
```sh
$ git clone https://github.com/FrozzDay/notflix && cd notflix
$ mv config.example config
$ chmod +x notflix
$ ./notflix
```
## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

