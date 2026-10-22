# AZ GROUP — From Local Trust to Global Systems

A monochrome, corporate-style website presenting AZ Group as a founder-led venture vision by Arpit Pareek. The first screen shows only a clickable AZ monogram; selecting it reveals the website. The page uses the supplied building, founder-office and community concept images, with restrained animation, responsive navigation and social-preview metadata.

## Files

- `index.html` — complete responsive website
- `az-group-building.jpg` — supplied architectural concept visual, used in the homepage hero
- `az-founder-office.jpg` — supplied founder-themed visual, used in the founder section
- `az-community-vision.jpg` — supplied community / hospitality concept visual
- `arpits-zone-logo.png` — supplied Arpit’s Zone logo, cropped for display
- `az-group-preview.jpg` — monochrome social preview card (1200 × 630)

All image paths are relative to the same folder as `index.html`. **Keep every file in the deployment root**; do not put them into a new assets folder unless you also edit their paths in the HTML.

## Publish on Netlify

1. Extract the ZIP.
2. Open your Netlify site dashboard and deploy the extracted folder containing `index.html` and all image files.
3. Confirm that the homepage loads and the images appear.
4. The social metadata currently points to `https://arpitszone.netlify.app/` and `https://arpitszone.netlify.app/az-group-preview.jpg`. If you deploy at another URL, update `canonical`, `og:url`, `og:image`, and `twitter:image` in the `<head>` of `index.html`.

## Publish with GitHub Pages

Upload `index.html`, `README.md`, and all image files to the published repository root. Keep the filenames unchanged, then commit the changes.

## Design notes

The visual system uses black, white and neutral grey, with disciplined typography, consistent spacing, responsive layouts and limited motion. The opening screen contains only the `AZ` monogram; click it to enter. No game-style power button or heavy 3D framework is used.

AZ Mart, AZ Cafe, AZ Logistics, AZ DevHub, AZ Studio and AZ Assets are presented as evolving concepts within the wider vision. The supplied architectural, founder-office and community visuals are illustrative artwork, not claims that a physical headquarters or each venture is currently operational.
