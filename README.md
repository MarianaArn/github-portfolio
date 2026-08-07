# Mariana Arnold | GitHub Portfolio

Professional digital portfolio for graduate information technology work and the MSIT 5910 Capstone Project.

## Published portfolio

https://marianaarn.github.io/github-portfolio/

## Featured capstone

The **Datacenter Deployment Tracking System (DDTS)** is a Flask web application designed to centralize datacenter rack deployment records, enforce a six-stage operational workflow, support role-aware access, and preserve an auditable history of status changes.

The portfolio case study documents the operational problem and project scope; layered Flask architecture; Python, Flask, Jinja2, Bootstrap, SQLAlchemy, SQLite, Alembic, and PyTest; authentication, CSRF protection, and role-based authorization; six-stage rack workflow validation; automated testing and performance baselines; Nginx, Gunicorn, and systemd deployment; and limitations, future work, and professional reflection.

## Portfolio structure

```text
.
├── index.html
├── README.md
├── assets/
│   ├── ddts-architecture.svg
│   ├── main.js
│   └── styles.css
└── projects/
    └── ddts.html
```

## Local development on Windows

```powershell
git clone https://github.com/MarianaArn/github-portfolio.git
cd github-portfolio
code .
```

For a simple local preview, use the VS Code Live Server extension or another static HTTP server.

## Git workflow

```powershell
git pull
git status
git add .
git commit -m "Describe the portfolio update"
git push origin main
```

GitHub Pages is configured to publish from the `main` branch. Relative paths are used throughout the site so it works under the `/github-portfolio/` project path.

## Accessibility and design

The portfolio uses semantic HTML, responsive layouts, keyboard-visible focus states, a skip link, descriptive alternative text, reduced-motion support, and high-contrast text. JavaScript is limited to progressive navigation behavior and the footer year, so the primary content remains available without scripting.

## Privacy

The public portfolio intentionally excludes passwords, secrets, private infrastructure details, production data, and other sensitive operational information.
