# Web Profile CI/CD

Static company profile website for FilkomTech Solutions, built with plain HTML and CSS. The page includes sections for About, Services, Team, and Contact, plus a light/dark theme toggle.

## Features

- Single-page layout with smooth anchor navigation
- Responsive hero and section layouts
- Contact form with simple client-side feedback
- Light/dark theme toggle stored in localStorage
- Dockerized with Nginx for static hosting

## Project Structure

- index.html: main page markup
- css/style.css: styling and layout
- Dockerfile: Nginx image for serving static files
- docker-compose.yml: compose definition for local container run

## Run Locally (No Docker)

Open index.html in a browser.

## Run with Docker

Build and run the container:

```
docker build -t web-profile-cicd .
docker run --rm -p 80:80 web-profile-cicd
```

Then open http://localhost.

## Run with Docker Compose

```
docker compose up --build
```

Then open http://localhost.
