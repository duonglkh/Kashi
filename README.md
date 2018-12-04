
<h1 align="center">Kashi</h1>
<p align="center">
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
![love](http://forthebadge.com/images/badges/built-with-love.svg)
</p>

![build](https://img.shields.io/badge/build-passing-brightgreen.svg?style=for-the-badge)  ![license](https://img.shields.io/badge/license-GPLv3-blue.svg?style=for-the-badge) ![license](https://img.shields.io/badge/PRs-welcome-yellow.svg?style=for-the-badge)

Kashi is a custom preset for [BetterTouchTool](https://folivora.ai/) that displays the current song's lyrics on the Macbook Pro's Touch Bar.

Kashi has three main functions:
- It gets local system data about the current song playing via Applescript.
- It queries [Genius API](https://docs.genius.com/) and validates for the most accurate search hit.
- It scrapes the raw HTML, formats and outputs the lyrics onto the Touch Bar.

Works with [Spotify](https://www.spotify.com/us/download/other/) and [iTunes](https://www.apple.com/itunes/download/).

## Installation

### Step 1: Install Dependencies
Kashi requires the following:
- [BetterTouchTool](https://folivora.ai/)
- [Python 3](https://www.python.org/downloads/release/python-371/)
  - [OSAscript](https://github.com/looking-for-a-job/osascript.py) - `pip3 install osascript`
  - [Requests](http://docs.python-requests.org/en/master/) - `pip3 install requests`
  - [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - `pip3 install bs4`
- An internet connection

### Step 2: Import Kashi Into BetterTouchTool
 1. Copy the entire contents of `kashi.json` onto your clipboard
 2. Go to the "TouchBar" section in BetterTouchTool's Preferences
 3. Paste

As Gordon Ramsay would say, **DONE**. You should see Kashi appear as a new widget.

## Planned Features
- Browser/web-player support: Youtube, Soundcloud, etc.
- Support for non-English languages.
