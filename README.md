# My Static Site

This is a simple static website built with HTML, CSS, and JavaScript, and deployed automatically to **Render**.

Every push to the `main` branch triggers an **automatic build and deployment** on Render.

## Deployed site

[Visit the live site](https://devops-2pia.onrender.com)

## 🧰 Tech Stack

- HTML / CSS / JS (Static)
- Nginx (Dockerized)
- Render (Hosting & CI/CD)

## ⚙️ Deployment Pipeline

Render is connected directly to this GitHub repository.  
Whenever a new commit is pushed to the `main` branch:
1. Render pulls the latest code.
2. Rebuilds the Docker image using the `Dockerfile`.
3. Deploys the new version automatically.

![Render Deploy](https://img.shields.io/badge/Render-Auto--Deploy-success?logo=render&color=46E3B7)
