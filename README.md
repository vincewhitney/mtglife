# MTG Life Counter

A simple mobile-friendly Magic: The Gathering life counter built as a single-page HTML app.

## Features

- Two-player life tracking
- Opponent-facing flipped display
- Tap controls for `+1`, `-1`, `+5`, `-5`, `+10`, `-10`
- Editable player names
- Dice roll for each player
- Coin flip for each player
- New Game button
- Damage taken and life gained tracking
- Game history saved locally
- Expandable game logs
- Works on phones, tablets, and desktop browsers

## How It Works

The app runs entirely in the browser using:

- HTML
- CSS
- JavaScript
- `localStorage` for saved game history

No server, backend, database, or login is required.

## Saving Data

Game history is saved locally on the user’s device/browser.

History will remain if the user:
- refreshes the page
- closes and reopens the browser
- returns to the same URL later

History may be lost if the user:
- clears browser data
- uses private/incognito mode
- switches devices
- switches browsers

## Deployment

This app can be hosted for free using GitHub Pages.

The main file should be named:

```text
index.html
