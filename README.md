# Rajesh & Monikha — Wedding Invitation

A static, single-page wedding invitation. No build step, no server logic.

## What to upload

When hosting, upload these together (the HTML references images by relative path):

```
Rajesh & Monikha.html
images/
  story-photo.jpg
  g1.jpg
  g2.jpg
  g3.jpg
  g4.jpg
  g5.jpg
```

You can **rename `Rajesh & Monikha.html` to `index.html`** so the URL is clean
(e.g. `https://yourname.github.io/wedding/` instead of `…/wedding/Rajesh%20&%20Monikha.html`).

## Host on GitHub Pages (free)

### Easiest way — via the GitHub website (no terminal needed)

1. Go to <https://github.com/new>
2. **Repository name**: `wedding` (or anything you like)
   **Visibility**: Public
   Click **Create repository**.
3. On the new empty repo page, click **uploading an existing file** (or the "Add file → Upload files" button).
4. Drag in:
   - `Rajesh & Monikha.html`  — **rename it to `index.html` first** by right-clicking on your computer
   - the whole `images/` folder
5. Scroll down, click **Commit changes**.
6. Go to **Settings → Pages** (left sidebar).
7. Under **Source**, choose **Branch: `main`**, **Folder: `/ (root)`**, click **Save**.
8. Wait 30–60 seconds. The page will show a green box with your URL, e.g.
   `https://<your-username>.github.io/wedding/`
9. Share that link!

### If you want a custom domain (optional)
- Buy a domain (e.g. `rajeshandmonikha.com`).
- In GitHub: Settings → Pages → add your **Custom domain**.
- At your domain registrar, add a CNAME record pointing to `<your-username>.github.io`.

## Editing later

- **Change text / dates / RSVP number**: open `Rajesh & Monikha.html` (or `index.html`), edit, commit again.
- **Replace photos**: drop new files into `images/` with the same filenames.
- **Phone number for RSVP** lives in two places — search for `9597275437` and update both.

## What's inside

- Live countdown to July 4, 2026 · 3:00 PM IST
- "Add to calendar" buttons (downloads .ics files)
- "RSVP on WhatsApp" deep-link (opens chat with pre-filled message)
- Google Maps link to the venue
- Mobile-responsive (tested down to 360px wide)
# rajeshmonikha
