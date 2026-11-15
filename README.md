# Days Until

A countdown app for the things you're waiting for. Add something with a date and it shows how many days are left, soonest first. Each countdown can have a photo background from your camera roll (with an optional darken switch), and a calendar view shows a coloured dot on every day that has something.

Live at **https://icnussa.github.io/days-until/**

## Install it on your phone

- **iPhone (Safari):** open the link, tap Share, then **Add to Home Screen**.
- **Android (Chrome):** open the link, tap the ⋮ menu, then **Install app**.

It then opens full screen with the hourglass icon and works offline.

## Notes

- Everything is saved on the device you use it on (IndexedDB). Nothing is uploaded anywhere.
- It's plain HTML, CSS and JavaScript with no build step. `index.html` is the whole app; `sw.js` adds offline support and `manifest.webmanifest` makes it installable.
