# Shimmer Tab - Modified

A customized build of [Shimmer Tab](https://github.com/dmitthedazed/shimmer-tab), 
a new tab extension for the [Helium browser](https://github.com/helium-browser/helium), 
originally built by [@dmitthedazed](https://github.com/dmitthedazed).

---

## What I Changed

- **Removed drop shadow from the settings panel**: Stripped the outer drop shadow (`box-shadow: none`) on the settings panel container for a clean, sleek, and minimalist appearance.
- **Added custom shortcut support**: Added an **"Add custom shortcuts"** feature at the end of the Backup settings section (where Export and Import are located):
  - Add individual shortcuts via Name and URL.
  - Import custom shortcuts by pasting JSON (`[{"name": "...", "url": "..."}]`) or link lists.
  - Upload `.json` files directly from your computer to load shortcuts into the extension.
  - Toggle between appending to or replacing existing home screen shortcuts.
  - Built-in active shortcuts manager to view all home screen shortcuts and remove any anytime with a single click.
  - Upgraded the default file Import button to automatically recognize and import raw shortcut arrays without throwing format errors.
- **Improved settings tab spacing**: Increased the spacing between the settings navigation tabs (`Look`, `Shortcuts`, `Widgets`, `Search`, `Data`) from `2px` to `6px`, with balanced container padding and smooth indicator pill transitions.
- **Cleaner project structure**:
  - Organized extension icons (`icon-16.png`, `icon-32.png`, `icon-48.png`, `icon-128.png`, and `favicon.svg`) into a dedicated `icons/` folder.
  - Moved `bangs.json` into its dedicated `bang/` folder.
  - Updated all references in `manifest.json`, `index.html`, and `assets/index-D0px3lmi.js`.

---

## How to Install

1. Download this repo as a ZIP (click **Code** then **Download ZIP**), or clone it:
   ```bash
   git clone https://github.com/<your-username>/shimmer-tab.git
   ```
2. Unzip the downloaded file (if you downloaded the ZIP).
3. Open your Chromium-based browser (Helium, Chrome, Brave, Edge, etc.) and go to the extensions management page:
   - In Helium / Chrome / Brave: `chrome://extensions`
4. Toggle on **Developer mode** in the top-right corner.
5. Click **Load unpacked** in the top-left toolbar.
6. Select the folder containing `manifest.json` (this repository's root directory).
7. Open a new tab to see and use your customized Shimmer Tab!
2. Open Helium and go to `chrome://extensions`
3. Turn on **Developer Mode** (top right toggle)
4. Click **Load unpacked** and select the downloaded folder

That's it, the extension should load right away.

---

## Credits

All original work belongs to [@dmitthedazed](https://github.com/dmitthedazed).  
This repo is just a modified build for personal use, shared for anyone who wants these tweaks.

Original repo: https://github.com/dmitthedazed/shimmer-tab

---

## License

See the [LICENSE](./LICENSE) file from the original project.

