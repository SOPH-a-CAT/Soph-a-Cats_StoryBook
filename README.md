# Parker & Pine Storybook

## [Open the storybook website](https://soph-a-cat.github.io/Soph-a-Cats_StoryBook/)

Click the link above to read and play. This GitHub repository contains the website’s source files.

An interactive picture-book website built with HTML, CSS, and JavaScript, without frameworks or libraries.

Read **Johnny Builds to Mars**, decorate and name a rocket, assemble its parts, and see the same creation return throughout the adventure. The site also includes book search, age filters, read-aloud support where available, and playful activities on each page.

## Run locally

From this repository, run:

```sh
python3 -m http.server 8765 --directory dist
```

Open http://localhost:8765 in your browser. No build or package installation is required. Any static web host can serve the contents of `dist/`.

## Files

- `dist/index.html`: bookshelf and reader structure
- `dist/app.js`: book catalog and navigation
- `dist/play.js`: story pages and interactive scenes
- `dist/workshop.js`: rocket drawing, naming, and saved designs
- `dist/style.css` and `dist/illustrated.css`: layout and styling
- `dist/assets/`: illustrated characters and backgrounds
- `ARTWORK.md`: AI-generated artwork provenance and prompts

Designs and reading progress are saved in browser localStorage on the current device. They are not uploaded to a server or synced between devices.

## Story content

Johnny Builds to Mars is currently an original demonstration story, pending the text of the intended published book. The other included stories are public-domain retellings.

Published site: https://soph-a-cat.github.io/Soph-a-Cats_StoryBook/
