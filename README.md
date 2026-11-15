# Issam Ahmed Al Balushi — Personal Website

A bilingual Arabic/English personal portfolio redesigned using the owner's supplied CV.

**Live website:** https://issamalbalushi.github.io/arabic-starter-website/

## Sections

- Professional introduction / About
- Experience (2017–2024 Oman Chamber of Commerce & Industry, 2013–2017 ASM Technologies, 2010–2012 3D Design LLC, 2007–2010 FOTO MAGIC)
- Selected initiatives and projects, with category filters
- Strategic management, digital innovation and creative expertise
- Education and selected professional training
- Email contact

## Features

- Responsive RTL/LTR design with Arabic as the default language
- English toggle; language preference saved locally in the browser
- Project filtering and expandable certificate listing
- HTML, CSS and vanilla JavaScript only; no build system
- No analytics, tracking or backend

## Source and privacy

Website content is adapted and condensed from **Issam Al Balushi CV.pdf** supplied by the owner. Some descriptions have been editorially summarized. The CV's specific street/neighborhood address, date of birth, and phone number are deliberately not displayed. The PDF is **not uploaded** to GitHub. The website displays a professional contact email and only city/country location.

The visuals used for project cards are conceptual, not actual screenshots.

## Edits and deployment

Edit `index.html` on the default `main` branch. The existing workflow under `.github/workflows/deploy.yml` automatically publishes the updated site via GitHub Pages.

The Arabic text is the initial element text; the English equivalent is stored in the `data-en` attribute. Language switching happens entirely in the browser.
