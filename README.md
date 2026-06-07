# Lab05 - Asynchronous JavaScript

A browser exercise for practicing Promises, `async`/`await`, and parallel asynchronous work. The page simulates loading pieces of random user information, with variable delays and possible failures.

## Intended behavior

- Fetch a user ID first
- Request first name, last name, username, email, and address asynchronously
- Use `Promise.all` to load independent fields in parallel
- Display an error when any request fails
- Optionally retry automatically when the resample checkbox is enabled
- Render the result in a Bootstrap form

## Technology

- HTML, CSS, and JavaScript
- Bootstrap
- Promises and `async`/`await`

## Run locally

Open `index.html` in a browser, or serve the directory with any static web server.

## Status

The page layout and initial `get_info()` Promise are present, but the remaining data functions and retrieval flow are still marked as TODO.
