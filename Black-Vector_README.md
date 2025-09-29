# Black-Vector

**Black-Vector** is a compact, hacker-styled web search console UI built with plain HTML, CSS, and JavaScript.
It provides a retro "console" look with quick search controls and specialized search modes (movies, images,
documents, songs and maps). It's designed as a front-end helper to craft search queries (including useful
Google dork-style queries) and open the results in a new tab.

---

## Features

- Dark / Light theme toggle with polished neon styling.
- Search types: Google (normal), Movie, Image, Document, Song, Map.
- File type pickers for movie/image/document/song modes.
- Map mode accepts a location name or latitude/longitude and opens Google Maps.
- Battery and CPU information display (browser-limited).
- Live footer clock and wallpaper switch support.
- Enter key triggers search (convenience).
- Provides dork-style queries to assist finding indexed files via search engines.

---

## Usage

1. Open `index.html` (the provided HTML file) in any modern browser.
2. Choose a search type from the dropdown.
   - For **Movie**, **Document**, **Image**, or **Song**, select a file type (e.g., `mp4`, `pdf`, `jpg`, `mp3`).
   - For **Map**, either type a place name or provide latitude and longitude.
3. Type your query in "Search Console" and press **Search** or the **Enter** key.
4. Results open in a new tab using Google Search, Google Images, or Google Maps depending on mode.

---

## Customization

- Modify `setTheme()` in the `<script>` section to change theme colors.
- Change background wallpaper by updating the `document.body.style.background` URL in the `window.onload` initializer or wire the `changeWallpaper()` function to a select input.
- Add more file types by editing `updateFileTypeOptions()` in the script.
- Adjust default wallpaper, fonts, or console visuals in the `<style>` block.

---

## Security & Privacy Notes

- This is a local front-end only UI. It opens search results in new browser tabs — it does not perform server-side scraping.
- Google "dork" style queries may return publicly indexed files; use responsibly and respect site owners' rights.
- Browser features like battery and hardwareConcurrency are limited by browser permissions and privacy settings.

---

## Files

- `index.html` — Main HTML/CSS/JS single-file front-end.
- `README.md` — (this file) usage and customization guide.

---

## License

MIT License — feel free to reuse and adapt. Attribution appreciated.

---

## Credits

Created from a user-provided HTML template. Design inspired by retro hacker console aesthetics.
