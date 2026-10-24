# SkillSprint Website

A responsive React + Vite frontend based on the supplied SkillSprint reference images.

## Run locally
1. Install Node.js (LTS) from https://nodejs.org/
2. Extract this project.
3. Open a terminal in this folder.
4. Run `npm install`
5. Run `npm run dev`
6. Open the local URL shown in the terminal (usually http://localhost:5173).

## Production build
Run `npm run build`; Vite creates the `dist` folder.

## Included screens
- Welcome / landing
- Sign in and create account
- Dashboard and progress cards
- Course catalogue, details and lesson screen
- Projects, filters, project details, new project and submission
- Job readiness checklist
- Profile and settings

## Notes
This is a frontend prototype. Authentication is simulated in the browser; Google sign-in requires OAuth setup. Uploaded files are selected locally and are not sent to a server. Lesson video playback, password reset email, persistent storage, and backend APIs are not configured. Connect a secure backend before production use.
