# Employability Skills Portfolio

Personal Employability Skills Webpage for the **New Venture Creation** module.

**Student:** Ion-Mirel Gozgar
**Student ID:** 25011328
**Assessment:** Task 3 — Employability Skills Webpage (20%)
**Learning outcome:** LO4 — Demonstrate attainment of employability skills in developing and presenting a new venture

---

## What is in this pack

```
employability-skills-webpage/
├── index.html        → the webpage (edit the text to match your own experience)
├── style.css         → all styling, no internet connection needed
├── README.md         → this file
├── .nojekyll         → tells GitHub Pages to serve the files as they are
└── images/
    └── placeholder.svg   → a stand-in shown until you add your real evidence
```

The page already works as it is. Before you submit, you should do two things: edit the wording so it is in your own voice, and swap the placeholder images for your real evidence.

---

## Step 1 — Personalise the content

Open `index.html` in any text editor (Notepad, VS Code, or the GitHub editor in the browser).

- The skills, reflection and references are written as a starting point. Change the wording so it describes what **you** actually did in the module.
- Your name and ID are already filled in. Check they are correct.

## Step 2 — Add your evidence images

1. Put your photos, screenshots or posters inside the `images` folder.
2. Name them simply, for example `evidence-1.jpg`, `evidence-2.png`.
3. In `index.html`, find each line that looks like:
   ```html
   <img src="images/placeholder.svg" alt="Placeholder for evidence one" />
   ```
   Change `images/placeholder.svg` to your file, for example `images/evidence-1.jpg`, and update the `alt` text to describe the image.
4. Update the caption underneath each image to say what the skill and the activity were.

Tip: keep each image under about 1 MB so the page loads quickly. JPG or PNG both work.

---

## Step 3 — Publish on GitHub Pages (free, gives you a live link)

You need a free GitHub account: https://github.com/signup

### A. Create the repository
1. Sign in to GitHub and click the **+** (top right) → **New repository**.
2. Repository name: `employability-skills` (or any name you like).
3. Set it to **Public**.
4. Do **not** tick "Add a README" (this pack already has one).
5. Click **Create repository**.

### B. Upload the files
1. On the new empty repository page, click **uploading an existing file**.
2. Drag in **all the files from this pack**, including the `images` folder and the hidden `.nojekyll` file.
3. Scroll down and click **Commit changes**.

### C. Turn on GitHub Pages
1. In the repository, open **Settings** → **Pages** (left menu).
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)**. Click **Save**.
4. Wait one or two minutes, then refresh. Your live link appears at the top of the Pages screen. It looks like:
   ```
   https://your-username.github.io/employability-skills/
   ```

That link is what you submit, or paste into your cover sheet.

---

## Editing later
You can change any file directly on GitHub: open the file, click the pencil icon, edit, then **Commit changes**. The live page updates within a minute or two.

## Working offline first
To preview before uploading, just double-click `index.html` and it opens in your browser. Everything works without an internet connection.
