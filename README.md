# Mahi — Reelmark-inspired Video Portfolio

A static HTML/CSS/vanilla JavaScript portfolio for GitHub Pages. The design keeps the soft mint Reelmark-inspired hero and curved draggable video carousel with 19 individual video demos. Video 5 (`1.5.mp4`) is intentionally excluded.

## Files
- `index.html` — single-page portfolio, styles, animation, video playback, reactions/ratings, review modal, and Contact form.
- `assets/videos/` — 19 MP4 demos.
- `assets/posters/` — matching video posters.

## Contact form
The contact form uses Formspree endpoint `https://formspree.io/f/xdeegwqd`. It includes name, email, subject, and message fields and displays an inline success/error message. The endpoint is a form ID, not a secret API key. Ensure the destination email is verified/active in your Formspree dashboard and test a submission before publishing widely.

## Run locally
From this folder run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages
Upload the contents of this folder to the repository root (including `assets/`) and enable Pages for the main branch/root.

## Notes
- Contact email: `mahi.sightsoftsolution@gmail.com`.
- Love reactions, star ratings and written reviews use `localStorage`, so they persist only in the same browser/device. Shared visitor feedback requires a backend.
- Only one video is allowed to play at a time.
- The Contact form needs internet access to send submissions to Formspree.


## Latest video replacement
The original website-showcase clip at `assets/videos/1.7.mp4` has been replaced with Mahi's `wifi-script9-full.mp4` video. Its poster is refreshed at `assets/posters/1.7.jpg`, and the card title is now **WiFi Repeater Product Film**. The other 11 portfolio videos remain unchanged.


## Additional videos added (2026-10-28)

Added the unique uploads `1.14.mp4` through `1.20.mp4`, with generated poster images and individual carousel cards. The newly uploaded `1.12(1).mp4` and `1.13(1).mp4` were exact SHA-256 duplicates of existing `1.12.mp4` and `1.13.mp4`, so they were intentionally not added again.
