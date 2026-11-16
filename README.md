# ishrakratul.github.io

Personal portfolio of **Ishrak Jahan Ratul**, Ph.D. candidate in Computer Science at Texas State University.

Live at: https://ishrakratul.github.io

## Updating the site

| What | Where |
|---|---|
| Profile photo | `assets/img/profile.jpg` (vertical portrait, about 4:5) |
| CV download | `assets/Ishrak_Jahan_Ratul_CV.pdf` (the CV buttons stay hidden until this file exists) |
| Gallery photos | `assets/photos/01.jpg` … `05.jpg`, then edit captions in the `PHOTOS` list near the bottom of `index.html` (the gallery stays hidden until at least one photo exists) |
| Roam with Ratul links | `SOCIAL` object near the bottom of `index.html` (empty = hidden) |
| Link preview image | `assets/img/og.png` (1200 × 630) |

## Before sharing the link

If some photos are not ready yet, open `index.html`, find `const HIDE_EMPTY_PHOTOS = false;` near the bottom, and change it to `true`. Any empty slot (cover, portrait, gallery) is then hidden instead of showing a placeholder.
