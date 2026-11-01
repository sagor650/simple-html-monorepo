# Simple HTML Monorepo

A beginner-friendly monorepo with **two plain HTML projects** and **one shared CSS file**. No Docker, Node.js, frameworks, or build commands required.

## Structure

```text
simple-html-monorepo/
├── apps/
│   ├── website/
│   │   └── index.html
│   └── admin/
│       └── index.html
├── packages/
│   └── shared-css/
│       └── style.css
└── README.md
```

## Run locally

1. Extract the ZIP.
2. Open the folder in VS Code (optional).
3. Open `apps/website/index.html` in any browser.
4. Click **Open Admin** to switch to the second HTML project.

You can also open `apps/admin/index.html` directly.

## What makes this a monorepo?

Both independent HTML apps and their shared CSS are stored in one Git repository. Updating `packages/shared-css/style.css` changes the styling of both apps.

## Push to GitHub

Create an empty repository at https://github.com/new, then run from the extracted project root:

```bash
git init
git add .
git commit -m "Initial HTML monorepo"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/simple-html-monorepo.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.
