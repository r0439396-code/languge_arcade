# Language Arcade

A language-learning arcade prototype by Ronin, with development support from Vex.

## Current prototype

- Daily Japanese multiple-choice lesson
- Earn 20 XP for a correct lesson answer
- Lesson completion unlocks the Word Match mini-game
- Earn 10 XP for a correct mini-game answer
- Local browser storage for prototype progress
- Responsive dark purple interface

## Run it

Open `index.html` in a modern browser, or serve this repository as a static website. No build step is required.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site. The Pages section will show the live URL.

## Important limitations

This is an early prototype, not a production-ready app.

- XP and lesson completion are stored only in this browser.
- Clearing browser data can erase progress.
- Local XP is not secure and must not be treated as verified.
- There is no account system, database, server-side XP validation, or cross-device sync yet.
- The current lesson is a single sample Japanese question, not a full course.
- Missing a day does not trigger a penalty.

## Planned milestones

1. Validate and improve the lesson and arcade experience.
2. Add a real lesson/course data model.
3. Implement offline XP batches with unique IDs and idempotent server verification (Pocket Verification System).
4. Add secure account and cross-device sync.
5. Expand language lessons, arcade games, and league progression.

## Team

- **Ronin** — Project lead
- **Vex (ChatGPT)** — Architecture and development support
- **Claude** — Code review and testing support
