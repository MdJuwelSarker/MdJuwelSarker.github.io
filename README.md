# Md Juwel Ahmed Sarker — Personal Academic Website

A clean, text-forward academic website: About, Research (job market paper, publications, working papers), Teaching, CV, and Contact. Plain HTML/CSS — no build tools, so you can edit any page directly in GitHub's website.

Once published this site will live at: **https://mdjuwelsarker.github.io**

---

## Part 1 — Reuse your existing "website" repo (5 minutes)

You already have a repo called `website` on your account. Instead of creating a new one, we'll rename it — this saves a step and avoids ending up with two half-built sites.

1. Log in to GitHub as **MdJuwelSarker** and open **https://github.com/MdJuwelSarker/website**.
2. Quickly glance at the file list — if there's anything in there you want to keep, stop and save/copy it elsewhere first (or tell me and I'll help you merge it in). If it's empty or just placeholder files, continue.
3. Go to the **Settings** tab of that repo.
4. Under "Repository name," change it to exactly: `MdJuwelSarker.github.io`
   (this exact spelling, matching your username's capitalization, is what tells GitHub to publish it as your main personal site).
5. Click **Rename**.
6. If the repo already has files in it that you're not keeping, delete them now: select all the files on the repo's main page, and use **Add file → Upload files** in Part 2 below to add the new ones — uploading a file with the same name will overwrite it, but leftover unrelated files should be deleted individually (click the file → the trash icon → Commit).

*(If you'd rather start completely fresh, you can instead create a brand-new repository at **https://github.com/new** named `MdJuwelSarker.github.io` and skip renaming — either path works.)*

## Part 2 — Upload the site files

You'll upload the contents of the folder I sent you (unzip it first — you should see `index.html`, `research.html`, `style.css`, an `assets` folder, etc. sitting directly inside, not inside an extra subfolder).

1. On your new (empty) repository page, click **"uploading an existing file"** (or **Add file → Upload files**).
2. **Drag the whole unzipped folder's contents** onto the upload box:
   - In **Chrome or Edge**, you can select all the top-level files *and* the `assets` folder together and drag them in one go — subfolders are preserved.
   - If your browser doesn't support dragging folders, upload the top-level files first (`index.html`, `research.html`, `teaching.html`, `cv.html`, `contact.html`, `style.css`, `.nojekyll`, `README.md`), then go into the `assets` folder locally and repeat with `assets/images/favicon.svg` and `assets/files/Sarker_CV.pdf` — when you type `assets/images/favicon.svg` as the target path GitHub creates the folders for you.
3. Scroll down and click **Commit changes** (the green button).

## Part 3 — Add your photo

1. In the repository, navigate into **assets → images**.
2. Click **Add file → Upload files**.
3. Upload your photo and, on the upload screen, rename it to exactly **`headshot.jpg`** (use a square photo, ideally at least 300×300px — GitHub lets you set the filename before committing).
4. Commit changes. The homepage will pick it up automatically (it already references `assets/images/headshot.jpg`).

## Part 4 — Turn on GitHub Pages

For a repo named `<yourusername>.github.io`, GitHub Pages usually turns on automatically. To confirm:

1. Go to your repo's **Settings** tab → **Pages** (left sidebar).
2. Under "Build and deployment," make sure **Source** is set to **Deploy from a branch**, branch **main**, folder **/ (root)**. Click **Save** if you had to change anything.
3. Wait 1–3 minutes, then visit **https://mdjuwelsarker.github.io** — your site should be live.

## Part 5 — Fill in the placeholders

I filled the site with everything from your CV, but a few things need your input before you send this link to search committees. Search the repo (or your local folder) for anything in *italics with brackets* — here's the full list, with the exact file to edit:

| What to add | File(s) | Where |
|---|---|---|
| Job market paper abstract (3–5 sentences) | `research.html` | "Job Market Paper" section |
| Job market paper link (PDF, SSRN, or working paper repository) | `index.html`, `research.html` | "Paper (PDF) — add link" |
| EDRE working paper number, once assigned | `research.html` | next to "EDRE Working Paper" |
| Google Scholar / ORCID / LinkedIn URLs | `index.html`, `contact.html` | replace the `href="#"` placeholders |
| Teaching philosophy (2–3 paragraphs, your voice) | `teaching.html` | "Teaching Philosophy" section |
| Courses you're prepared to teach | `teaching.html` | "Courses I Am Prepared to Teach" |
| Your photo | `assets/images/headshot.jpg` | see Part 3 |

**To edit any page:** open the file on GitHub, click the pencil icon (top right of the file view) to edit it right in your browser, make your change, then click **Commit changes** at the bottom. The live site updates within a minute or two.

## Notes

- The **Download CV (PDF)** button links to `assets/files/Sarker_CV.pdf`, generated from the Master CV you uploaded. When you update your CV, export a fresh PDF (Word → File → Save As → PDF) and upload it to `assets/files/` with the same filename to replace it.
- Reference contact information (your recommenders) was intentionally left off the public site — it's still in the full PDF, per standard practice for what goes on a public webpage versus a CV sent directly to a search committee.
- If you'd rather use a custom domain later (e.g. `juwelsarker.com`), that's a separate step (buying the domain + adding a `CNAME` file) — ask me when you're ready and I'll walk you through it.
