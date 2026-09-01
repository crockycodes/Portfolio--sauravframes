[README.md](https://github.com/user-attachments/files/31672859/README.md)
# Portfolio-@sauravframes
Personal portfolio website showcasing my video editing and motion design work, built with HTML, CSS, and JavaScript. Featuring selected projects, services, workflow, and contact information.
# Saurav Frames — Portfolio

A single-page portfolio site for **sauravframes**, a video editing and motion design service. Built with plain HTML/CSS/JS — no build step, no dependencies.

**Live site:** https://sauravframes.netlify.app

## What's here

- `index.html` — the entire site (markup, styles, and a small script all in one file)
- `videos/` — drop your exported reel clips here (`clip-01.mp4`, `clip-02.mp4`, etc.) to have them appear in the Work section

## Sections

- **About** — who Saurav is and what he does
- **Work** — a film-bin style grid of video clips
- **Services & pricing** — Basic / Premium / Advanced tiers
- **Process** — how a project runs, brief to delivery
- **Contact** — Instagram, email, and phone

## Adding a new clip

1. Export the reel as an `.mp4` (H.264) file
2. Drop it into `videos/` following the existing naming pattern (`clip-0N.mp4`)
3. Add a matching `<div class="clip">` block in the Work section of `index.html`, or reuse an existing slot by swapping the `src` and the category/title text
4. Clips autoplay muted and loop; if a file is missing or fails to load, a placeholder is shown instead of a broken video

## Deployment

Currently deployed via **GitHub Pages** (`main` branch, root) at the link above.

> Note: the site is also deployed on **Netlify**. Running two live deployments from the same repo isn't a problem by itself, but it does mean two URLs exist for the same site — worth deciding which one is the "real" link to share, and unpublishing the other from its settings page to avoid confusion (or keep both if you have a reason to, e.g. Netlify as a staging/faster host and Pages as a backup).

## Local development

No build tools needed — just open `index.html` in a browser, or use a local server (e.g. VS Code's Live Server extension) for the best experience with video playback and relative paths.
