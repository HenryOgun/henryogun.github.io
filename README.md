# henryogun.com — Personal Portfolio

Personal professional website for Henry Olabode Ogun, showcasing software development projects, broadcast engineering work, audio samples, and client work.

🔗 **Live:** [henryogun.com](https://www.henryogun.com)

---

## Features

- Project portfolio with live demos and descriptions
- Blog powered by Sanity CMS
- Audio samples from broadcast and production work
- Client work showcase
- Auto-deployed to Whogohost via GitHub Actions on every push to `main`

---

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **CMS:** Sanity.io
- **CI/CD:** GitHub Actions → FTP deploy to Whogohost
- **Hosting:** Whogohost shared hosting

---

## Deployment

Every push to `main` triggers a GitHub Actions workflow that:
1. Builds the React app with Vite
2. FTP-syncs the `dist/` output to the live server

---

## Author

**Henry Olabode Ogun**  
Full Stack Software Engineer · Broadcast Systems Engineer  
✉️ henryoogun@gmail.com
