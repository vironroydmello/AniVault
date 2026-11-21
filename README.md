# AniVault

A single-page anime watchlist and taste tracker. No build step and no server: plain HTML, CSS and JavaScript.

- Statuses (plan to watch, watching, watched, dropped) and 1-10 ratings
- Predicted scores for unwatched titles, based on your own ratings
- Taste profile with genre averages, rating distribution and tag affinities
- Copy a prompt for any AI chat, paste its reply back, and add the suggestions to your list
- Works offline once loaded, and can be installed to a phone or desktop home screen

Your list is saved in your browser's local storage. Use **Taste profile > Copy backup** to keep a copy, and **Import** to restore it on another browser or device.

## Run it on GitHub Pages

1. Create a new repository and upload every file from this folder to the root (including `.nojekyll`).
2. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Run it locally

Open `index.html` in a browser. To test the install and offline features, serve the folder instead: `python3 -m http.server 8000` and visit `http://localhost:8000`.
