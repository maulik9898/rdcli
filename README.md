Rdcli
===

[![npm version](https://badge.fury.io/js/rdcli.svg)](https://badge.fury.io/js/rdcli)
[![Build Status](https://travis-ci.org/stoneo/rdcli.svg?branch=master)](https://travis-ci.org/stoneo/rdcli/)
[![npm download](https://img.shields.io/npm/dt/rdcli.svg)](https://www.npmjs.com/package/rdcli)
[![Code Climate](https://codeclimate.com/github/stoneo/rdcli/badges/gpa.svg)](https://codeclimate.com/github/stoneo/rdcli)

> The simple way to download and unrestrict DDL files, torrents and magnets.

[![asciicast](https://raw.githubusercontent.com/stoneo/rdcli/master/screencast.gif)](https://raw.githubusercontent.com/stoneo/rdcli/master/screencast.gif)

## Installation

`npm install --global rdcli`

And set your real-debrid account as enviroment variable on your `~/.bashrc`

```bash
export REALDEBRID_USERNAME=your_username
export REALDEBRID_PASSWORD=your_password
```

## Usage

`rdcli <url|magnet|torrent>`

Download DDL file:

`rdcli http://uptobox.com/1gdncohxbqkp`

Download magnet file:

`rdcli 'magnet:?xt=urn:btih:33130de5c14a8bb5410746ee5a9604cdfb9538ef'`

Download torrent file:

`rdcli Back.to.the.Future.Trilogy.1080p.BluRay.x264.torrent`

## Development

Install dependencies:

`make install`

Start project:

`make run`

Run tests:

`make test`

License
---

MIT

**Free Software, Hell Yeah!**
