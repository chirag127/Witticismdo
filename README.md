# Witticismdo

> Browser extension that shows a random joke every time you click it.

[![Live](https://img.shields.io/badge/live-Witticismdo.oriz.in-6c5ce7)](https://Witticismdo.oriz.in)
[![Stars](https://img.shields.io/github/stars/chirag127/Witticismdo?style=social)](https://github.com/chirag127/Witticismdo/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

Click the toolbar icon and Witticismdo pops up a fresh dad joke, fetched live from [icanhazdadjoke.com](https://icanhazdadjoke.com/). Pin the extension for one-click laughs.

Live page: https://Witticismdo.oriz.in

## Install

### Chrome / Edge (desktop)
1. Download this repo as a [ZIP](https://github.com/chirag127/Witticismdo/archive/refs/heads/main.zip) and unzip it.
2. Open `chrome://extensions` (or `edge://extensions`).
3. Enable **Developer mode**.
4. Click **Load unpacked** and select the unzipped folder.
5. Pin the extension, then click it for a joke.

### Mobile (Kiwi Browser)
1. Install [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser).
2. Go to `kiwi://extensions/`.
3. Enable **Developer mode**.
4. Choose **Install from zip** and pick the downloaded ZIP.

### Use as a plain web page
1. Unzip the folder and open `popup.html` in any browser.
2. Reload the page for a new joke.

## How it works
`script.js` fetches a joke from the icanhazdadjoke Slack endpoint and renders it into `popup.html`. No build step, no dependencies.

## Tech
HTML, CSS, vanilla JavaScript, Manifest V2.

## License
[MIT](./LICENSE)
