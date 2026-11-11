# English LZK practice app

Upload the files in this folder to the root of a GitHub repository and enable **GitHub Pages** from the repository settings.

- `index.html` contains the complete app.
- `.nojekyll` keeps GitHub Pages in simple static-site mode.
- No external libraries, images, or audio files are required.

## Device-local progress

The app stores sound preference and exercise results in the browser's `localStorage` on each device. For each completed exercise it remembers the **last score, best score, and number of attempts**. This stays on that browser/device and is not uploaded to GitHub or sent anywhere.

Clearing browser/site data or using a different browser/device starts with fresh progress.
