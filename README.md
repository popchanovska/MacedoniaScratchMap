# MacScratch — (Design & Architecture of Software)

## Summary
MacScratch is a small client-side web application created for the *Design & Architecture of Software* course. The app demonstrates browsing cultural and historical places on a map, filtering and searching, user registration/login, and list management (planned, visited, favorites). The original project includes a short video demo that illustrates the functional and non-functional requirements.

## Application flow
The application begins with a navigation interface that allows users to explore different sections through the navigation bar and buttons on each page. Access to personal lists (planned, visited, favorites) and the feedback form requires user authentication — if the user is not logged in, they are redirected to the login page.

From the map view, users can browse cultural and historical places and use filters to search by place name or city/municipality. If a searched place is not found in the database, a message is displayed in the console.

Users can register new accounts and log in with existing ones. The system validates user input — errors appear for existing usernames, incorrect passwords, or mismatched passwords during registration.

After logging in, users can add places to their personal lists. Each place can only be added once to prevent duplicates. Other system functionalities demonstrate proper handling of input validation, navigation, and user access control.

## Installation & running locally
1. Clone and checkout the branch:
```bash
git clone https://github.com/popchanovska/MacedoniaScratchMap
cd MacedoniaScratchMap
git checkout Homework_3
