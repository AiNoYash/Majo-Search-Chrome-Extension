# Majo Search

[Chrome Web Store Link](https://chromewebstore.google.com/detail/majo-smartest-ctrl+f-find/hlakcdjgidoppjilpbephlhkfbkdmdco)

Majo Search is a powerful Chrome extension that upgrades your standard on-page search (Ctrl+F) with advanced algorithms like fuzzy matching, phonetic search, and regex support.
Works on any Chromium browser.

## How to Use (Manual Installation)

1. Unzip the `build.zip` file.
2. Open your browser and go to the extensions page (e.g., `chrome://extensions/`).
3. Turn on **Developer mode**.
4. Click **Load unpacked**.
5. Select the root folder from the unzipped files (the folder containing `manifest.json`).

## Developer Setup

To build the extension from source, you need to compile its individual modules.

1. Open your terminal.
2. Navigate into each of the following directories (running them in separate terminals is recommended for continuous development):
   - `page-options`
   - `page-boarding`
   - `content`
   - `background`
3. In each directory, run the following command for continuous building:
   ```bash
   npm run watch
   (Use npm run build instead if you only need a single build).
4. Once built, go to your browser's extensions page, enable Developer mode, click Load unpacked, and select the root directory containing manifest.json.
