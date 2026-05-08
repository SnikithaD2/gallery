# 📸 BTech Memories Gallery — 2023–27 💕

A beautiful pink-themed polaroid photo gallery with login protection.

## Project Structure

```
btech-gallery/
├── index.html      ← Login page
├── gallery.html    ← Photo gallery
├── style.css       ← All styles
├── images/         ← PUT YOUR PHOTOS HERE 📸
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── ...
└── README.md
```

## How to Add Photos

1. Copy your photo files into the `images/` folder.
2. Open `gallery.html` in a text editor.
3. Find the `const images = [...]` array near the bottom.
4. Add a new entry for each photo:

```js
{ file: 'yourphoto.jpg', date: 'Month Year', caption: 'A fun caption 💕' },
```

That's it! Refresh the page and your new polaroid will appear automatically.

## How to Run

Just open `index.html` in any browser. No server needed!

> **Tip:** If photos don't load, make sure the filenames in the `images` array
> exactly match the files in the `images/` folder (case-sensitive).

