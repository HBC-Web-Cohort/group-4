# HBC Learning Hub — Guided Learning Edition

A responsive React + Vite learning hub prototype for beginner front-end students.

## Features
- Guided curriculum in recommended order: Start Here, HTML, CSS, JavaScript, React.
- Lesson pages include learning goals, short notes, code examples, external reading, video embeds/search links, and quick multiple-choice checks.
- Mark lessons complete and track overall/path progress.
- Study planner supports adding, completing, filtering and deleting tasks.
- Lesson progress and planner tasks persist in localStorage on the current browser/device.
- Responsive desktop, tablet and mobile layouts.

## Run locally
1. Install Node.js LTS if it is not installed.
2. Extract this ZIP.
3. Open the extracted `hbc-learning-hub-next` folder in VS Code.
4. Open the terminal in the folder that contains `package.json`.
5. Run:
   - `npm.cmd install`
   - `npm.cmd run dev`
6. Open the local URL shown in the terminal (usually `http://localhost:5173`).

On macOS/Linux use `npm install` and `npm run dev`.

## Notes
- This is a front-end prototype, not a multi-user platform. Progress is stored only in the current browser using localStorage; it does not sync between devices or student accounts.
- Some lessons embed a known freeCodeCamp video; other lessons link to YouTube search results so the learner can choose an up-to-date beginner tutorial. Article links point to MDN or the official React documentation.
- External video/article links require internet access. YouTube embeds may be unavailable on some networks; use the YouTube link instead.
- Before submission, add the approved team member names, review all content and links, run `npm.cmd run build`, push the project to GitHub, and deploy on Vercel.

## Suggested team contribution
- Teammate A: dashboard, navigation, responsive layout.
- Teammate B: curriculum and lesson content.
- Teammate C: study planner, localStorage and quiz interactions.
- All teammates: test on phone/desktop, contribute commits, review README and prepare demo.
