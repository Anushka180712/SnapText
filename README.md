# SnapText

Take a photo, keep only the text.

SnapText is a small phone web app. You point your camera at something, it reads the text right on your phone, saves the text as a note, and throws the photo away. The photo is kept only when you switch on **Keep the photo too** for that capture (or **Always keep photos** in Settings).

**Open it:** https://anushka180712.github.io/SnapText/

## What it does

- Big **Take photo** button that opens the camera. You can also pick an existing photo or screenshot.
- Reads the text on the phone itself (Tesseract.js). Nothing is uploaded anywhere.
- Saves each result as a note you can edit, copy, share, search, or delete.
- Photos are not saved unless you ask, so your gallery and storage stay clean.
- Works offline after the first use, and can be added to your home screen like an app.
- Languages: English, Hindi, English + Hindi, and a few European languages (Settings).

## Try it on your phone

**Android (Chrome)**
1. Open https://anushka180712.github.io/SnapText/ in Chrome.
2. Tap the three dots (top right) and choose **Add to Home screen** or **Install app**.
3. Open SnapText from your home screen and tap **Take photo**. Allow the camera if asked.
4. The first reading takes a little longer (it downloads the reader once, about 5 MB).

**iPhone (Safari)**
1. Open https://anushka180712.github.io/SnapText/ in Safari.
2. Tap the **Share** button (square with an arrow), scroll down, tap **Add to Home Screen**, then **Add**.
3. Open SnapText from your home screen and tap **Take photo**, then **Take Photo** in the menu.
4. After the shot, tap **Use Photo**. The text appears and is saved.

## Notes

- Notes are stored in the browser on that phone. Deleting the app or clearing browser data deletes them, so use **Settings → Download all as .txt** for a backup.
- Photos taken through SnapText do not go to your gallery.
- Best results: good light, text filling most of the frame, phone held flat.

## Files

`index.html` (the whole app), `sw.js` (offline support), `manifest.json` and icons (home-screen install). No build step: GitHub Pages serves the files as they are.
