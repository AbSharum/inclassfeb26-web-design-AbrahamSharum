[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/74uxI-YA)
# inClassFeb26
Web Page Design Pair inClass Competition

---

## Implementation Notes

A single static page (no server-side code, no build tooling) written for an in-class pair exercise on how a browser resolves and loads a page over HTTP.

- `class.html` — a page walking through the browser/server request lifecycle (URL parsing, DNS resolution, TCP connection, HTTP request/response, rendering), styled with `class.css` and a `background.jpg`. Attributed in the page footer to "Ab, Issac, and Vincent."
- `class.css` — page styling (background image, fonts, layout).
- `background.jpg` — background image used by `class.css`.

### How to run

No build step or server required:

1. Open `class.html` directly in a browser, **or**
2. Serve the folder with any static file server, e.g.:
   ```
   python -m http.server 8000
   ```
   then visit `http://localhost:8000/class.html`.
