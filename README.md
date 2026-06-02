# Shrutika Mohan Shinde E-Portfolio

A static e-portfolio site for Shrutika Mohan Shinde, built as a standalone HTML page with separately hosted image assets.

## Live Site

After GitHub Pages finishes publishing, the portfolio will be available at:

https://shreyashp3.github.io/Shrutika-ePortfolio/

## Files

- `index.html` is the hosted portfolio page.
- `assets/` contains the optimized portfolio images.
- `assets/image-links.js` can point images to Google Drive links for non-GitHub editing.
- `EDIT_IMAGES_WITHOUT_GITHUB.md` explains the Drive-based image replacement workflow.
- `GOOGLE_SITES_NATIVE_PLACEHOLDERS.md` gives the exact native Google Sites build order with image placeholders.
- `google-sites-native-placeholders.html` is a visual no-image placeholder reference.

## Open Locally

Open `index.html` in a browser, or run:

```powershell
npx --yes serve .
```

Then open the local URL shown in the terminal.

## Google Sites

In Google Sites, use `Insert -> Embed -> URL` and paste the live site URL above. Google Sites will display the hosted portfolio inside an iframe.

Google Sites cannot directly edit images inside that iframe. To let editors change photos without GitHub access, use the Google Drive workflow in `EDIT_IMAGES_WITHOUT_GITHUB.md`.

If images must be changed by clicking Google Sites image blocks, rebuild the page natively in Google Sites using `GOOGLE_SITES_NATIVE_PLACEHOLDERS.md`. That version should use Google Sites `Insert -> Image` blocks instead of the embedded GitHub page.
