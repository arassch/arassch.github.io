# arassch.github.io

Personal robotics portfolio, served by GitHub Pages at https://arassch.github.io

## Publish it (one-time)

1. On GitHub, create a new **public** repository named exactly `arassch.github.io`.
2. Upload the contents of this folder (`index.html`, `assets/`, `README.md`) plus your CV saved as `cv.pdf`.
3. In the repo go to **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. After a minute the site is live at https://arassch.github.io

## Add a video

1. Upload the video to YouTube (Unlisted is fine if you don't want it in your channel feed).
2. Copy the ID from the URL: `https://www.youtube.com/watch?v=XXXXXXXXXXX` → `XXXXXXXXXXX`.
3. In `index.html`, replace `data-youtube="VIDEO_ID"` with `data-youtube="XXXXXXXXXXX"`.

## Add a project

Copy one `<article class="card"> … </article>` block in the Projects section and edit the title, tags, text, code link and video ID.

## Still to fill in

- Project description for the Isaac Lab demo (marked TODO)
- Links to each publication (marked TODO, currently `href="#"`)
- `cv.pdf` (your robotics CV)
