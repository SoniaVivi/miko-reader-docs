---
sidebar_position: 1
---

# Getting Started

Miko Reader is a webapp that utilizes the Mangadex API to fetch and display manga and the AniList API to manage users personal manga lists.

## Running a local copy

[Clone the repository](https://github.com/SoniaVivi/miko-reader) to a directiory of your choosing

Install dependencies by running:

```bash
yarn
```

Run the development server:

```bash
yarn devstart
```

## File Structure of /src

Top level files are any Redux slices and store, index.js, Routes.js, dateHelpers.js (to format dates), and style.scss.

- `/src/assets` Contains fonts, SVG components, and a placeholder profile image for non-logged in users.

- `src/stylesheets` Holds Sass mixins and links to fonts

- `/src/components` Contains all non-SVG React components and hooks.
