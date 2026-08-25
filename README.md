# Path Finder

Path Finder is a career and course guidance web app for students, designed to help them explore future pathways based on their interests, strengths, and personality.

## Features

- Career quiz and matching logic
- Course and career recommendations
- Personalised study pathway suggestions
- Saved careers and dashboard tracking
- Career comparison section
- AI-style career guidance assistant
- Local account sign-up/login using browser storage

## Running locally

Open the project in a browser using a local web server:

```bash
cd "C:\Users\User\Desktop\path finder"
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/index.html
```

## GitHub Pages deployment

Because this is a static single-page app, it can be deployed directly to GitHub Pages.

1. Push the repository to GitHub.
2. In the GitHub repository, open Settings.
3. Go to Pages.
4. Select the branch to deploy from (for example, `main` or `master`).
5. Set the folder to `/root`.
6. Save.

A `.nojekyll` file is included to help ensure the static site is served correctly.

## Project structure

```text
.
├── index.html
├── README.md
├── .nojekyll
└── .gitignore
```

## Notes

This project stores user data in the browser using `localStorage`, which is suitable for a demo or prototype but not for production authentication or real student data.
