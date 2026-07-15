# Jassco Construction Website

A static 4-page website (Home, About, Services, Contact) for Jassco Construction, ready to host free on GitHub Pages.

## Files

- `index.html` — Home page
- `about.html` — Company history and approach
- `services.html` — Services and project types
- `contact.html` — Contact info and message form
- `style.css` — Shared styling
- `nav.js` — Mobile menu toggle

## Publish it on GitHub Pages (free hosting)

1. **Create a GitHub account** at github.com if you don't have one.
2. **Create a new repository:**
   - Click the **+** icon (top right) → **New repository**
   - Name it something like `jassco-construction` (any name works)
   - Set it to **Public**
   - Do NOT add a README, .gitignore, or license (this project already has its files)
   - Click **Create repository**
3. **Upload the site files:**
   - On the new repo page, click **uploading an existing file**
   - Drag in all 6 files from this folder (`index.html`, `about.html`, `services.html`, `contact.html`, `style.css`, `nav.js`)
   - Scroll down and click **Commit changes**
4. **Turn on GitHub Pages:**
   - Go to the repo's **Settings** tab
   - Click **Pages** in the left sidebar
   - Under **Build and deployment → Source**, select **Deploy from a branch**
   - Under **Branch**, choose `main` and folder `/ (root)`, then click **Save**
5. **Get your live link:**
   - Wait 1–2 minutes, then refresh the Pages settings screen
   - Your site will be live at:
     `https://<your-github-username>.github.io/<repository-name>/`
   - Example: `https://jassco.github.io/jassco-construction/`

## Making updates later

Edit any file directly on GitHub (pencil icon on the file page) and commit — the live site updates automatically within a minute or two.

## Notes on the contact form

The contact form uses a `mailto:` action, so submitting it opens the visitor's email app pre-addressed to jassoroger@yahoo.com — no backend or paid form service required. If you'd like a form that submits silently in the browser instead, a free service like [Formspree](https://formspree.io) can be swapped in later.

## Swapping in real photos/logo

Each page currently uses simple line-drawing placeholders instead of photos. To add real images:

1. Add your image files (e.g. `logo.png`, `job-photo-1.jpg`) to this same folder
2. Replace the placeholder `<svg>...</svg>` blocks (inside `.visual-block` or the header logo) with `<img src="job-photo-1.jpg" alt="...">`
