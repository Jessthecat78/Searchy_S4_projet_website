# Searchy - Showcase Website

This repository contains a simple showcase website for the **Searchy** project.
The site is built with **HTML and CSS only** (no JavaScript, no external dependencies).

## Project files

- `index.html`
  - Home page.
  - Presents the Searchy project, its objective, and a short overview.

- `avancement.html`
  - Progress page.
  - Shows the current project state, including the completed console prototype and next planned steps.

- `contact.html`
  - Contact page.
  - Contains 4 member cards with placeholders for photo, first name, last name, and role.

- `style.css`
  - Shared stylesheet for all pages.
  - Includes reusable classes (cards, grids, navigation, section spacing, status badges) and responsive rules.

## Structure choices

- Semantic HTML is used on all pages:
  - `header` for navigation
  - `main` for content
  - `section` for page blocks
  - `footer` for bottom information
- Internal navigation links are local only:
  - `index.html`
  - `avancement.html`
  - `contact.html`

## Responsive behavior

- On large screens: content uses multi-column layouts.
- On small screens: grids collapse to a single column for readability.

## How to open the site

Open `index.html` in a browser, then navigate using the top menu.
