# Y. Dharmini — Portfolio

A responsive, accessible personal portfolio built with HTML, CSS, and vanilla JavaScript. The content uses details supplied in Dharmini's resume and certificates.

## Run locally

Open `index.html` in a browser, or open this folder in Visual Studio Code and use a local web server extension such as Live Server.

## Update content

- Edit personal information, experience, skills, projects, and credentials in `index.html`.
- Adjust colors, spacing, and responsive layouts in `style.css` using the variables at the top of the file.
- The mobile navigation, current footer year, and subtle scroll reveals are in `script.js`.
- Replace `assets/profile.jpeg` to change the portrait. Keep the same filename or update its path in `index.html`.
- Certificate images and PDFs are stored in `assets/`. Replace files or update their links and labels in the certification section.
- Project demo links are plain anchors in the project cards; update the `href` values when a URL changes.

## Publish

This is a static site and does not require a build step or backend. It can be hosted on GitHub Pages or any static web host by publishing this folder. Keep the `assets` folder alongside `index.html` so images and certificate files resolve correctly.

## Accessibility and search

The page uses semantic headings and sections, a skip link, keyboard focus styles, responsive layouts, reduced-motion support, and descriptive image text. Resume keywords appear as selectable text rather than being embedded in images.
