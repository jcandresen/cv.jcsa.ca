
# Jonas Andresen's CV Website

This repository contains the source code for Jonas Andresen's CV webpage, showcasing his professional experience, skills, and education. The website is built as a simple static webpage using HTML and is hosted using GitHub Pages.

## Table of Contents

- [Overview](#overview)
- [File Structure](#file-structure)
- [Favicons](#favicons)
- [Customization](#customization)
- [Deployment](#deployment)

## Overview

This website is designed to provide a concise and professional online presence for Jonas Andresen, highlighting his career in IT administration. The site includes sections for a professional summary, work experience, education, skills, and languages.

## File Structure

- `index.html`: The main HTML file for the webpage.
- `favicon/`: A folder containing all favicon and web icon assets.
  - `favicon_black.ico`, `favicon_white.ico`: Main favicon files for dark and light modes.
  - `favicon-16x16_black.png`, `favicon-16x16_white.png`: 16x16 favicon files for dark and light modes.
  - `favicon-32x32_black.png`, `favicon-32x32_white.png`: 32x32 favicon files for dark and light modes.
  - `apple-touch-icon_black.png`, `apple-touch-icon_white.png`: Icons for Apple devices.
  - `android-chrome-192x192_black.png`, `android-chrome-192x192_white.png`: 192x192 icons for Android devices.
  - `android-chrome-512x512_black.png`, `android-chrome-512x512_white.png`: 512x512 icons for Android devices.
  - `site_black.webmanifest`, `site_white.webmanifest`: Web manifest files for PWA support.
- `README.md`: This file, providing information about the repository.

## Favicons

The website is equipped with dynamic favicons that change based on the user's system color scheme (light or dark mode). This is achieved using media queries in the HTML `<head>` section.

### Example:
```html
<link rel="icon" href="favicon/favicon_black.ico" type="image/x-icon">
<link rel="icon" href="favicon/favicon_white.ico" type="image/x-icon" media="(prefers-color-scheme: dark)">
```

## Customization

You can easily customize the content of the webpage by editing the `index.html` file. The following sections can be updated:
- **Professional Summary**
- **Work Experience**
- **Education**
- **Skills**
- **Languages**

If you need to update the icons, place your updated favicon files in the `favicon/` folder and adjust the file paths in `index.html`.

## Deployment

This website is hosted using GitHub Pages. To deploy updates:
1. Make changes to the `index.html` or any other file.
2. Commit and push the changes to the `main` branch.
3. GitHub Pages will automatically update the live site.

