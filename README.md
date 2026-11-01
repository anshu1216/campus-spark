# Campus Spark — UIC Virtual Campus Time Capsule

A small, browser-based prototype for the University Institute of Computing community at Chandigarh University, Gharuan/Kharar, Punjab.

## Run it

For a quick preview, open `index.html` in a modern browser. To install it as an app, the files need to be served from a local web server or hosted website (browsers do not enable app installation from a `file://` page). In the project folder, run `py -m http.server 8000`, then open `http://localhost:8000` in Chrome or Edge and choose the install icon in the address bar or the browser menu's **Install Campus Spark** option. Entries are stored in that browser's local storage, so they remain on the same device and are not shared with other students.

To save a copy, keep the complete `CampusSpark` folder together. You can copy it to a USB drive or upload it to your own cloud storage. The `manifest.json`, `sw.js`, and `icon.svg` files are required for installable/offline-app behavior.

## What the prototype does

- Accepts an anonymous good-news moment and a theme.
- Creates a short headline with a local rule-based helper.
- Adds a floating spark to the capsule and updates a simple weekly recap.
- Persists the demo entries in browser local storage.

## AI project opportunity

This prototype was built with AI assistance, but it does **not** call a generative AI service yet. The headline helper in `index.html` is deterministic JavaScript and can be explained as a safe offline prototype. A full MCA project can replace that helper with an approved language-model API to generate headlines, classify themes, and write a recap. Keep student submissions anonymous, avoid sending personal or sensitive information, and have a human review AI-generated content before publication.

## Suggested project title

**Campus Spark: An AI-Powered Virtual Campus Time Capsule for UIC, Chandigarh University**

## Suggested demo flow

1. Add a short positive campus story and select a theme.
2. Show the new spark, headline, count, and updated recap.
3. Explain the difference between the current offline helper and a future AI API integration.

This is a front-end prototype, not a shared multi-user service. For a real campus-wide version, add a backend, moderation, authentication or abuse controls as appropriate, and faculty approval for data handling.
