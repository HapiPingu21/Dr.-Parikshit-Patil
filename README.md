# Dr. Parikshit Patil — Website

A lightweight, responsive website built for GitHub Pages. There is no database, paid hosting dependency, or build step.

## Preview locally

From this folder, run a small local web server:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the main branch and `/ (root)`, then save.

The website will appear at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Edit without touching code

1. Visit [Pages CMS](https://app.pagescms.org/) and sign in with GitHub.
2. Install/authorize the Pages CMS GitHub app for this repository.
3. Select **Website content**.
4. Edit a field and save. Pages CMS commits the change to GitHub; GitHub Pages republishes automatically.

To replace the main photograph, open **Doctor portrait**, select or upload a JPG, PNG, or WebP image, and save. A vertical portrait with the doctor's face centred works best.

The editable fields live in `content/site.json`. The CMS form is defined in `.pages.yml`.

## Before launch

- Confirm current hospital/clinic, role, consultation address and timings.
- Confirm which phone number should receive calls and WhatsApp messages.
- Replace the CV-sourced portrait with an original high-resolution photograph supplied by Dr. Patil.
- Ask Dr. Patil to medically review all service descriptions.
- Add a direct LinkedIn URL if desired.
- Do not publish patient photographs or testimonials without explicit written consent.
