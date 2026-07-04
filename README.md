# Majo Search

**Chrome Web Store:**  
https://chromewebstore.google.com/detail/majo-smartest-ctrl+f-find/hlakcdjgidoppjilpbephlhkfbkdmdco

Majo Search is a powerful Chrome extension that upgrades your standard on-page search (**Ctrl + F**) with advanced search algorithms such as **fuzzy matching**, **phonetic search**, and **regular expression (regex)** support.

Compatible with any **Chromium-based browser**.

---

## Manual Installation

1. Extract the contents of `build.zip`.

2. Open your browser's extensions page:

   - **Chrome:** `chrome://extensions/`
   - **Microsoft Edge:** `edge://extensions/`
   - **Brave:** `brave://extensions/`

3. Enable **Developer mode**.

4. Click **Load unpacked**.

5. Select the extracted root folder (the one containing `manifest.json`).

6. The extension is now installed and ready to use.

---

## Developer Setup


### 1. Build the Extension

Each module is built independently. Open a separate terminal for each of the following directories:

- `page-options`
- `page-boarding`
- `content`
- `background`

Install dependencies for each:

```bash
npm install
```

Navigate into each directory and start watch:

```bash
npm run watch
```

> **Note:** If you only need a one-time production build, use:
>
> ```bash
> npm run build
> ```

---

### 2. Load the Extension

1. Open your browser's extensions page.

2. Enable **Developer mode**.

3. Click **Load unpacked**.

4. Select the project's root directory (the folder containing `manifest.json`).

The extension will now be loaded and will automatically update whenever the watched modules are rebuilt.
