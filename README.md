# Itch.Io-TagShield

# Hide Games on itch.io

A Firefox extension that hides games on [itch.io](https://itch.io) by genre (Visual Novel, Survival, Adventure and more). You choose exactly which genres to hide with simple checkboxes.

> **Note:** For now this extension works **only on Firefox**. It has **not been tested** on Chromium-based browsers (Chrome, Edge, Brave, etc.), so it may not work there.

## Features

- Pick which genres to hide, one by one
- Works on browse pages, search results and collections, including games that load as you scroll
- On/off toggle for the extension
- Add custom genres
- Your choices are saved in the browser

## Installation (development)

1. Download or clone this repository.
2. In Firefox, open `about:debugging#/runtime/this-firefox`.
3. Click **Load Temporary Add-on…** and select the `manifest.json` file.

The extension is removed when Firefox is closed. For a permanent install, it needs to be signed on addons.mozilla.org, or you can use Firefox Developer Edition/Nightly.

## Usage

1. Click the extension icon in the Firefox toolbar.
2. Check the genres you want to hide.
3. Games of those genres disappear from itch.io pages right away.

## Limitations

- itch.io game cards only show each game's main genre, not all of its tags, so the extension filters by that genre.
- Firefox only for now (see the note above).

## License

Released under the [MIT License](LICENSE).
