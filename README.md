<h1 align="center">BiTiEs</h1>
BASH Torrent Search a.k.a BiTiEs is a shell script to search and get magnet link. Forked from <a href="https://github.com/Bugswriter/notflix">Bugswriter</a>

### How does this work?

This is a shell script. It scrape 1337x and TPB to get the magnet link.
You can use this by using option + argument, or just run it.
For scraping script use simple gnu utils like sed, awk, paste, cut.
Tracker List is provided by [ngosang](https://github.com/ngosang/trackerslist) and [XIU2](https://github.com/XIU2/TrackersListCollection)
## Requirements

## Execute
```sh
$ git clone https://github.com/FrozzDay/BiTiEs && cd BiTiEs
$ mv config.example config
$ chmod +x bities tracker
$ ./bities
OR
$ ./bities -a "Search something here"
```
## Updating Tracker List on config file
```sh
$ ./tracker

```

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

