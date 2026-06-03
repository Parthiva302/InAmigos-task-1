# Personal Profile Website

A clean, minimalist personal profile site template built with plain HTML and CSS. Mobile-friendly and easy to customize.

## Overview

This repository includes a single-page profile website with these sections:
- Hero / Header (name, role, short intro)
- About Me
- Skills (tags)
- Contact (email, LinkedIn, location)
- Footer

## Quick Preview

Open `index.html` in your browser to preview the site locally.

## Files

- `index.html` — main HTML page (edit content here)


## How to Customize

1. Replace text content in `index.html`:
	- Change your name in the `h1` with class `name`.
	- Update the role/tagline in the paragraph with class `tagline`.
	- Edit the short intro paragraph with class `intro`.
	- Update the `About Me` paragraph in the `#about` section.
	- Edit skills in the `ul.skills` list (add/remove `<li>` items).
	- Update contact info in the `#contact` list (email link, LinkedIn URL, location).

2. Adjust colors and fonts in `styles.css` using CSS variables at the top:

	- `--accent` — primary accent color
	- `--bg` — page background
	- `--surface` — surface/card background
	- `--text` and `--muted` — text colors

	Example: change the accent color by editing the `:root` variables.

3. Typography: the page uses a system font stack. To use a web font, add a link to the font in the `<head>` of `index.html` and update `font-family` in `styles.css`.

4. Add your photo

	- Save your profile photo to `assets/photo.jpg` (create the `assets` folder in the project root if it doesn't exist).
	- The site will automatically display the image if it exists; otherwise a tasteful SVG placeholder is shown.


## Accessibility & Best Practices

- Anchor links include `rel="noopener noreferrer"` and open external links in a new tab.
- Focus styles are provided for keyboard users.
- Content uses semantic sectioning (`header`, `section`, `footer`) for improved screen reader support.

## Responsive Behavior

The layout is mobile-first and uses a max-width container. A small media query applies subtle card styling on larger screens.

