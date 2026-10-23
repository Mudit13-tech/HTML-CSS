# HTML & CSS clones

Front-end practice: recreating well-known websites with plain HTML and CSS,
no frameworks and no JavaScript.

## YouTube homepage

`YOUTUBE-CLONE/` rebuilds the YouTube home page:

- Header with the logo, search bar, voice search and notification count
- Sidebar with Home, Subscriptions, Originals, YouTube Music and Library
- Video grid with thumbnails, channel avatars, titles, view counts and upload age; it drops from three columns to two below 750px

The styles are split by area: `header.css`, `sidebar.css`, `video.css`, and
shared rules in `general.css`. Icons are local SVGs in `icons/`.

## Run

No build step. Open the page in a browser:

```bash
open YOUTUBE-CLONE/yt.html
```
