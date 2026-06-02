# Edit Images Without GitHub Access

Google Sites cannot edit images inside the embedded GitHub Pages iframe. The workaround is to keep the design on GitHub Pages, but point the image tags to Google Drive files that other people can replace.

## One-Time Setup

1. Create a Google Drive folder for the portfolio images.
2. Upload the 15 images using these exact names:

```text
shrutika_01.jpg
shrutika_02.jpg
shrutika_03.jpg
shrutika_04.jpg
shrutika_05.jpg
shrutika_06.jpg
shrutika_07.jpg
shrutika_08.jpg
shrutika_09.jpg
shrutika_10.jpg
shrutika_11.jpg
shrutika_12.jpg
shrutika_13.jpg
shrutika_14.jpg
shrutika_15.jpg
```

3. Share each image so anyone with the link can view it.
4. Copy each image share link into `assets/image-links.js`.
5. Commit and push once.

After this one-time setup, non-GitHub editors can update images from Google Drive.

## How Editors Replace An Image Later

1. Open the Google Drive folder.
2. Right-click the existing image file, for example `shrutika_05.jpg`.
3. Use the Drive option to upload a new version of that same file.
4. Do not delete the file and upload a new one, because that changes the file ID.

The GitHub Pages site and the Google Sites embed will keep using the same Drive file link, so the image updates without repo access.

## Google Sites Embed URL

Use this in Google Sites:

```text
https://shreyashp3.github.io/Shrutika-ePortfolio/
```
