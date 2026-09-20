# Arun Gopi — Personal Website

Professional portfolio for [Arun Gopi](https://www.linkedin.com/in/itsarung/), Mainframe
Modernization Architect. Built with plain HTML/CSS/JS &mdash; no build step, no dependencies.

## Hosting on GitHub Pages

1. Create a GitHub repository named exactly:
   ```
   <your-username>.github.io
   ```
   (Replace `<your-username>` with your GitHub username, e.g. `itsarung.github.io`.)

2. Push this folder to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: personal website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```

3. GitHub Pages will serve the site automatically at:
   ```
   https://<your-username>.github.io
   ```

   GitHub Pages serves files from the repository root of a `<username>.github.io` repo &mdash;
   no Settings action needed. (For a normal repo instead, enable Pages at
   *Settings &rarr; Pages &rarr; Deploy from a branch &rarr; main &rarr; / (root)*.)

## Customization

- Update the email address in `index.html` (`mailto:you@example.com`).
- Colors and fonts are controlled by CSS variables at the top of `style.css`.
- Content sections live in `index.html` &mdash; About, Experience, Skills, and Highlights.

## Local preview

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.