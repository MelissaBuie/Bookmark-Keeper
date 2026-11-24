# Bookmark Keeper

A small web app for saving your favorite websites. Add a site's name and URL, and it shows up as a card with its favicon. Bookmarks are saved in your browser, so they are still there when you come back.

**Live demo:** https://the-codingphoenix.github.io/Bookmark-Keeper/

<!-- Add a screenshot: save one as screenshot.png and uncomment the next line -->
<!-- ![Bookmark Keeper screenshot](screenshot.png) -->

## Features

- Add a bookmark through a pop-up form
- Checks that both fields are filled in and that the URL is valid (regex validation)
- Shows each site's favicon, name and link
- Delete bookmarks you no longer want
- Saves everything to `localStorage`, so bookmarks persist between visits

## Built with

- HTML5
- CSS3 (responsive layout)
- JavaScript (DOM manipulation, `localStorage`, form validation)
- Font Awesome icons

## What I learned

- Saving and loading data with `localStorage` and `JSON.stringify` / `JSON.parse`
- Validating user input with a regular expression
- Rebuilding a list in the DOM every time the data changes

## Run it locally

Clone the repo and open `index.html` in your browser. No install needed.
