# The game's website

This is a one-page site: the hook, gameplay video, features, screenshots and a press kit. It's plain HTML, needs no build step, and costs nothing to host.

## Recommended host: GitHub Pages (free)

1. Make a free account at github.com. Create a **public** repository, for example `royal-heart-site`.
2. Upload everything in this `website/` folder to it: drag and drop works on github.com.
3. In the repository, open **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. After a minute the site is live at `https://YOUR-NAME.github.io/royal-heart-site/`.
5. **Optional:** buy a domain such as `royalheartgame.com` (about $12 a year at any registrar), add it under **Settings → Pages → Custom domain**, and tick **Enforce HTTPS**.

**Other options considered:**
- **itch.io:** free. Best for hosting a **playable web demo** and for indie discovery. Put a page up there too when the demo exists, but only the demo, never the full game.
- **Carrd:** about $19 a year. Easy drag-and-drop pages, but no video hosting and less control.
- **Wix or Squarespace:** monthly fees, and heavier than this game needs.

## Before going live

Search `index.html` for **TODO** and fill in:
- the **Steam store link** (Wishlist button and footer), once the Coming Soon page exists;
- the **Discord invite** link;
- the **press email**.

Then add the gameplay video: copy a clip from `mockups/trailer_clips/` to `website/video/gameplay.webm`. Use the finished trailer once it's cut. Keep it under about 25 MB so GitHub handles it comfortably; for bigger files, upload to YouTube and embed that instead.
