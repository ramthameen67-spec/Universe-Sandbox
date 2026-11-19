# Universe Sandbox

A 3D space physics sandbox that runs in the browser. Build solar systems, stars, black holes, and moons, then press play and watch gravity do its thing.

It's a single file, `index.html`, with no build step and no installs.

## Run it

**Option 1: Open it directly.** Double-click `index.html` to open it in your browser.

**Option 2: GitHub Pages.** Upload `index.html` to the root of a repository, then go to **Settings → Pages**, choose the `main` branch and `/ (root)`, and save. The site will be at `https://<your-username>.github.io/<repo-name>/`.

## Controls

- **Drag** to orbit the camera. **Scroll** or pinch to zoom.
- **Tap an object** to select it and see its details.
- **Play / pause** and the speed controls sit in the bottom bar.
- **+ (Add)** opens the object palette. Drag objects into the scene.
- **Scenes** loads premade systems.
- **Menu** has settings, help, the laser and move tools, achievements, save and load, and background choices.

## Apex AI (optional)

Apex AI can design a solar system from a text description. It uses Google's Gemini API, so it needs a free key:

1. Get a key at [aistudio.google.com/apikey](https://aistudio.google.com/apikey).
2. Open **Apex AI**, tap the **API key** button, paste the key, and tap **Save key**.

The key is stored only in your browser's local storage. It is never written into the game file. Anyone with access to the page's source can still see a key you use in your own browser, so don't paste a key into a copy of the file that you share publicly.

## Saving

**Save** stores the current scene in your browser's local storage. Clearing your browser data will delete saved scenes.

## Files

- `index.html`: the whole game (HTML, CSS, and JavaScript).
- `index.txt`: the same file with a `.txt` extension, for anyone who wants it as plain text.
- `README.md`: this file.
