# CRAVE Campaign — Sneha Manhas | Trackzio Assignment

A single-page HTML site: Sneha's intro, the brief, the Big Idea, and all 6
deliverables (real swipeable Instagram carousel, static posts, memes, and the
reel) with the "what/how/why" answers written out clearly for the interviewer.

No build step. Just `index.html` + an `assets/` folder next to it.

## How to put it on GitHub Pages

### Option A — one file at a time (what you did last time, works fine)

1. Create a new **public** repo at https://github.com/new (e.g. `crave-campaign`)
2. **Add file → Upload files** → drag in `index.html` → Commit
3. **Add file → Upload files** → drag in `README.md` → Commit
4. For every file inside the `assets` folder, upload it the same way, but
   **rename it in the filename box to include the `assets/` prefix** before
   committing:
   - `assets/crave-logo.png`
   - `assets/carousel-1.png`
   - `assets/carousel-2.png`
   - `assets/carousel-3.png`
   - `assets/post-room-for-craving.png`
   - `assets/post-lunchbox-promised.png`
   - `assets/meme-relationship-status.png`
   - `assets/meme-lunch-avengers.png`
   - `assets/reel.mp4`
   - `assets/reel-poster.jpg`
   - `assets/sneha-manhas-cv.pdf`
5. Once done, open the repo's file list and confirm there's **one `assets`
   folder** containing all 11 files.

### Option B — drag the whole folder at once (faster)

Unzip this download, then in **Add file → Upload files**, drag in `index.html`
and the entire `assets` folder (the folder icon itself) together in one go.

### Turn on GitHub Pages

1. **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, folder: **/(root)** → **Save**
4. Wait ~1 minute — your link appears:
   `https://<your-username>.github.io/<repo-name>/`

### Quick check it worked

Visit `https://<your-username>.github.io/<repo-name>/assets/crave-logo.png`
directly — if the CRAVE logo shows up on its own, everything else on the page
will load too.

## Notes

- The Instagram carousel is a real swipeable component — drag it with a mouse
  on desktop, or swipe with a finger on mobile, just like the actual app.
- The reel autoplays muted (like real Instagram) — tap the speaker icon on it
  to unmute.
- "Download CV" pulls from `assets/sneha-manhas-cv.pdf` (converted from the
  original Word doc for anyone to open without Word).
