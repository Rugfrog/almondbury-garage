# Almondbury Garage

One-page website for Almondbury Garage, Upper Bankfield Mills, Almondbury Bank, Huddersfield HD5 8HF.

Plain HTML, no build step: `index.html` plus the logo and icons in `assets/`.

## Changing things

- **Phone number:** find and replace `01484 546693` and `01484546693` in `index.html`.
- **Call-back form:** get a free access key from [web3forms.com](https://web3forms.com) and paste it into `FORM_ACCESS_KEY` near the bottom of `index.html`. Until then the form asks people to ring.
- **Opening hours:** the table in the "Find us" section, the footer, and `HOURS` in the script at the bottom (used for the "Open now" badge).
- **Photos:** the ones in `assets/img/` are free stock photos from Pexels (free for commercial use, no credit needed), standing in until there are real photos of the garage. Swap them for real photos using the same file names. Landscape works best.

## Going live on almondburygarage.co.uk

Remove the `<meta name="robots" content="noindex">` line, then either upload the folder to the existing hosting, or point the domain at GitHub Pages.
