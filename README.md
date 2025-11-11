# MacScratch — Homework (Design & Architecture of Software)

## Summary
MacScratch is a small client-side web application created for the *Design & Architecture of Software* course. The app demonstrates browsing cultural and historical places on a map, filtering and searching, user registration/login, and list management (planned, visited, favorites). The original project includes a short video demo that illustrates the functional and non-functional requirements.

## Demo video (notes)
Demo video with the following guide:
- 0:00–1:00 — Navigation and page walkthrough (click nav buttons and page buttons). Access to lists and feedback requires login — unauthenticated users are redirected to the login form.
- 1:00–2:00 — Map view and filtering inputs; searching by place name and city/municipality is supported. If a place is not found in the DB, a console message appears.
- 2:00–3:00 — User registration and login flows; errors are shown for existing usernames, wrong passwords, or mismatched passwords.
- 3:00–end — Adding places to lists; adding the same place multiple times does not duplicate it. Other system requirements are demonstrated.

## Installation & running locally
1. Clone and checkout the branch:
```bash
git clone https://github.com/popchanovska/MacedoniaScratchMap
cd MacedoniaScratchMap
git checkout Homework_3
