# YouTube Clone - Web & Git Lab Task

A frontend clone of the YouTube homepage created as part of our university lab assignment. This project demonstrates basic frontend web development using HTML and CSS along with standard Git workflow for version control.

## About the Project
The goal of this project is to build a responsive YouTube-like interface from scratch without using any external UI frameworks or templates. It replicates the core layout and styling of YouTube desktop and mobile views.

## What is Included
- **Header Navigation:** Includes the YouTube logo, a functional search bar with search and voice buttons, and user profile/action icons arranged using CSS Flexbox.
- **Fixed Sidebar:** A navigation panel on the left containing links for Home, Shorts, Subscriptions, Library, and History using the `<nav>` element.
- **Topic Filter Bar:** Horizontal category chips to filter content.
- **Video Grid:** A responsive video card layout built with CSS Grid. Each card displays:
  - Video thumbnail
  - Video title
  - Channel name with a verified badge
  - Views count and upload time
- **Card Hover Effects:** Hover animations including slight elevation, shadows, and subtle thumbnail scaling.
- **Responsive Layout:** Media queries to make the interface adjust smoothly on desktops, tablets, and mobile screens.

## Project Structure
```text
youtube-ui/
├── images/             # Logos, avatars, and video thumbnails
├── index.html          # HTML structure
├── style.css           # Styling, Flexbox, Grid, and media queries
└── README.md           # Project documentation
```

## Technologies Used
- **HTML5**
- **CSS3** (Flexbox, CSS Grid, Media Queries)
- **Git & GitHub** (Version Control)

## Git Workflow Followed
1. Initialized local repository (`git init`)
2. Added project files to staging (`git add .`)
3. Committed changes (`git commit -m "..."`)
4. Connected local repo to GitHub (`git remote add origin ...`)
5. Pushed code to the remote repository (`git push -u origin main`)

## How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/saeedansari9t9/youtube-ui-uni-assignment.git
   ```
2. Open `index.html` in any web browser.