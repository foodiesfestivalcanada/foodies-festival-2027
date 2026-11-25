# Foodies Festival 2027 — Vendor Applications

A responsive static website built with HTML, CSS and vanilla JavaScript for publishing on GitHub Pages. No build step or backend is required.

## Project structure

```text
foodies-festival-2027/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    └── images/
        ├── foodies-logo.png       # Add the official supplied logo
        ├── gallery-01.jpg         # Add official festival photograph
        ├── gallery-02.jpg
        ├── gallery-03.jpg
        ├── gallery-04.jpg
        └── gallery-05.jpg
```

The gallery tiles are labelled placeholders until the corresponding images are added. The logo has a text fallback, so the page remains usable before the logo file is added. The event artwork is CSS illustration, not a claim to show official event photography.

## 1. Create a GitHub repository

1. Sign in to [GitHub](https://github.com/).
2. Select **New repository**.
3. Give it a name, for example `foodies-festival-2027`.
4. Choose Public (or confirm your preferred visibility and Pages eligibility).
5. Create the repository.

## 2. Upload the website

1. Open the new repository.
2. Select **Add file → Upload files**.
3. Upload `index.html`, `styles.css`, `script.js` and `README.md` into the repository root.
4. Create the `assets/images/` folders and upload the image files listed above into `assets/images/`.
5. Commit the changes.

Keep the filenames and letter case exactly as shown. GitHub Pages paths are case-sensitive.

## 3. Enable GitHub Pages

1. In the repository, open **Settings**.
2. Select **Pages** in the left-hand menu.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Select **Save**.

## 4. Find the published website URL

Return to **Settings → Pages**. GitHub will display the published site URL after deployment completes. It normally follows this pattern:

`https://YOUR-USERNAME.github.io/foodies-festival-2027/`

The exact URL depends on your GitHub username and repository name.

## 5. Add or replace the logo, photos, social links and app link

### Official logo

Download the official Foodies Festival logo from the supplied logo folder:

`https://drive.google.com/drive/folders/1ONWXqBMKuYNIb2rSljau6GKNCGqcXfrn`

Upload the chosen logo image to `assets/images/` and name it exactly:

`foodies-logo.png`

If the original logo is JPG or WebP, either convert it to PNG or update both `src="assets/images/foodies-logo.png"` references in `index.html` (header and footer) and the favicon/social image references in the `<head>`.

### Festival photographs

Download the selected photographs from the supplied folder:

`https://drive.google.com/drive/folders/1s-EGrI-KPOtrlQuWoBAPhxv0mDwQjUUG`

Upload five images using these exact filenames:

- `assets/images/gallery-01.jpg`
- `assets/images/gallery-02.jpg`
- `assets/images/gallery-03.jpg`
- `assets/images/gallery-04.jpg`
- `assets/images/gallery-05.jpg`

The gallery buttons already point to these paths. To add more gallery tiles, duplicate a `.gallery-tile` button in `index.html` and update its `data-gallery-image` path and accessible label. Use direct image files in the repository; a Google Drive folder URL is not a direct image URL.

### Main assets folder

The supplied main assets folder is:

`https://drive.google.com/drive/folders/1iPozvN94gr5fZOAfIQRxpJ_o9padTUOr`

Download any approved brand assets you want to use and upload them into `assets/images/`. This project does not assume that it can read files from the Drive folder automatically.

### Videos

The two supplied Google Drive video preview URLs are embedded in `index.html`. If playback is blocked, open each video's Drive sharing settings and set General access to **Anyone with the link — Viewer**. Do not change the supplied video IDs unless you intend to replace the videos.

### Social links and app link

In `index.html`, find the footer's `.social-links` and `.app-link` anchors. Replace each `href="#"` with the official Facebook, Instagram, Twitter, YouTube and app destination URLs when supplied. Do not leave `#` placeholders in the published version if you want those links to work.

The app link is a separate footer item and should point directly to the app, not a social page or group.

## 6. Update event details and application URLs

In `index.html`, find the `<!-- FESTIVAL LOCATIONS -->` section by searching for the event names:

- Brighton — 1–3 May 2027 — Preston Park, Brighton  
  `https://forms.gle/UnJWGFbuZVYTv3YJ9`
- Bath — 21–23 May 2027 — Royal Victoria Park, Bath  
  `https://forms.gle/Rv2wLnhvD7RY8WnKA`
- London — 29–31 May 2027 — Syon Park, London  
  `https://forms.gle/SWzJC5YwPgg1yeUp7`
- St Albans — 4–6 June 2027 — Oaklands College, St Albans  
  `https://forms.gle/ar5641Hg3BvzJhQH6`

Each card has its own application URL. Update the matching `href` only when a form changes.

Exhibitor pricing is in the `#opportunities` section of `index.html`. The supplied rates are:

- Space-only pitches: **£200 per square metre + VAT**
- Exhibitor marquees: **£247 per square metre + VAT**
- Artisan producers market: **£395 + VAT per stall**

Check all edited event details and prices before committing changes.

## Important pre-publication checklist

- [ ] Add the official logo as `assets/images/foodies-logo.png`.
- [ ] Add official gallery images (or keep the clearly labelled placeholders until ready).
- [ ] Confirm both Drive videos are shared with “Anyone with the link — Viewer”.
- [ ] Replace all four social links and the app link with official URLs when available.
- [ ] Test all four application buttons and the contact email link.
- [ ] Check the published site on a phone and desktop.

## Notes

- This is a static website. Application data is collected by the supplied Google Forms, not by this website.
- No attendance figures, sales guarantees, unprovided venue addresses, phone numbers, booth dimensions or unsupported programme details have been added.
- The displayed footer copyright is the exact text supplied: `© 2024 Foodies Festival. All rights reserved.`
