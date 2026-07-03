# Careers Page — Deploy for Free on GitHub Pages

This is a self-contained static site: one `index.html` plus a `jobs/` folder for your PDFs. No build step, no server, no cost.

## 1. Create a GitHub account (skip if you have one)
https://github.com/join — free.

## 2. Create a new repository
- Click **New repository** (top right → the `+` icon).
- Name it anything, e.g. `careers` or `yourcompany-careers`.
- Set it to **Public**.
- Click **Create repository**.

## 3. Upload these files
- On your new repo's page, click **Add file → Upload files**.
- Drag in `index.html` and the whole `jobs` folder (with your PDFs inside).
- Scroll down, click **Commit changes**.

## 4. Turn on GitHub Pages
- Go to the repo's **Settings** tab → **Pages** (left sidebar).
- Under "Build and deployment", set **Source** to `Deploy from a branch`.
- Branch: `main`, folder: `/ (root)`. Click **Save**.
- Wait ~1 minute. Your site will be live at:

  `https://YOUR-USERNAME.github.io/REPO-NAME/`

  e.g. `https://acme-corp.github.io/careers/`

## 5. Add a job posting
1. Put the JD PDF in the `jobs/` folder (upload via **Add file → Upload files**, choosing the `jobs` folder).
2. Open `index.html` in the repo, click the pencil (✏️) icon to edit.
3. In the `jobs` array near the bottom, add a new entry — copy the format of the existing ones.
4. Commit changes. The live page updates within a minute or two.

## 6. Link it from LinkedIn
Once live, copy your page URL (or a specific PDF's direct link, e.g.
`https://YOUR-USERNAME.github.io/REPO-NAME/jobs/senior-backend-engineer.pdf`)
and paste it into your LinkedIn hiring post or the comments.

---

### Optional: custom domain
If you own a domain (e.g. `careers.yourcompany.com`), you can point it at this
GitHub Pages site for free — GitHub Pages → Settings → Pages → "Custom domain."

### Editing without git knowledge
Everything above uses GitHub's web upload/edit buttons — no terminal or git commands needed.
