# Soft Girl Library ♡

A cute, pastel reading tracker built as a static GitHub project.

## Features
- Add, edit, and remove books
- Organize books into Want to Read, Currently Reading, and Finished
- Track pages read, ratings, and personal reviews
- Set an annual reading goal and view reading statistics
- Save favourite quotes with book and page references
- Keep a dated reading journal
- Search and filter your bookshelf
- Export a JSON backup

## Run it
Open `index.html` in a modern browser, or enable GitHub Pages in **Settings → Pages** and publish from the `main` branch, root folder.

## Storage and privacy
All library content is stored in this browser's `localStorage`. It is not uploaded to GitHub or any database. This means:
- Your entries stay on this browser and device.
- A different browser/device starts with an empty library.
- Clearing browser site data can erase the library.
- Use the **Backup** button regularly to download a JSON copy.

The repository currently contains only the application source. Do not add private reading notes, passwords, or personal data to committed files. If you want the source itself private, set the GitHub repository visibility to **Private**.

## Fonts
The interface uses elegant serif and handwritten-style system fallbacks so it works without external font services. To use licensed font files such as Cutie Patootie, Always in My Heart, Haliman, Cutiepop, Bunch Blossoms, Girly, or Autumn in November, add the font files you own or are licensed to use in an `assets/fonts/` folder and define matching `@font-face` rules in the stylesheet. Font names alone do not include the actual font files.
