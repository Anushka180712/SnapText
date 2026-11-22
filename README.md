# SnapText

Take a photo, keep only the text.

SnapText is a small phone web app. Tap the camera, take a photo, tap **Use Photo**, and the text lands in one big text box while the photo is thrown away. Take as many photos as you like: each one adds its text below the last, in order. The photo is kept only when you switch on **Keep the photo too** before shooting, and then it stays as a photo only, without adding text.

**Open it:** https://anushka180712.github.io/SnapText/

## What it does

- One running text box. Every photo adds its text to the end; you can type, fix or delete anything in it.
- Clean, readable text: broken lines are joined back into sentences, bullet lists stay as lists, stray symbols are dropped.
- Shoot back-to-back: photos are read one after another in the background, a badge shows how many are waiting.
- Photos are not saved unless **Keep the photo too** is on for that shot (or "Keep photos by default" in Settings). A kept photo stays as a photo only, and its text is not added to the box.
- Changed your mind? Your last few photos stay as faded "Keep?" thumbnails for 24 hours (or until Clear all). Tap one and choose **Keep this photo**; its text is taken out of the box. Photos you never keep are thrown away.
- **Copy all** copies the whole text (plus kept photos, for apps that accept them). **Share all** sends text and kept photos to any app, ChatGPT included. **Clear all** empties everything, with Undo.
- Text is read on the phone itself (Tesseract.js), nothing is uploaded. Works offline after the first use.
- Languages: English, Hindi, English + Hindi, French, German, Spanish (Settings).

## Try it on your phone

**Android (Chrome)**
1. Open https://anushka180712.github.io/SnapText/ in Chrome.
2. Tap the three dots (top right) and choose **Add to Home screen** or **Install app**.
3. Open SnapText from your home screen and tap the blue camera button. Allow the camera if asked.
4. The first reading takes a little longer (it downloads the reader once, about 5 MB).

**iPhone (Safari)**
1. Open https://anushka180712.github.io/SnapText/ in Safari.
2. Tap the **Share** button (square with an arrow), scroll down, tap **Add to Home Screen**, then **Add**.
3. Open SnapText from your home screen and tap the blue camera button, then **Take Photo**.
4. After the shot, tap **Use Photo**. The text appears in the box. Repeat for more photos.

## Notes

- The text is stored in the browser on that phone until you tap Clear all. Clearing browser data also deletes it.
- Photos taken through SnapText do not go to your gallery.
- Best results: good light, text filling most of the frame, phone held flat.

## Files

`index.html` (the whole app), `sw.js` (offline support), `manifest.json` and icons (home-screen install). No build step: GitHub Pages serves the files as they are.
