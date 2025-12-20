# Happy-Birthday-Crush (giftforjoysree)

A simple, single-file static site you can customize and publish as a birthday gift.

---

## Quick local preview ✅
- Open a terminal in this project folder and run one of the following:
  - Python (works in most systems with Python 3):

    ```bash
    python -m http.server 8000
    # open http://localhost:8000 in your browser
    ```

  - VS Code: install the **Live Server** extension and click "Go Live" on `index.html`.

Note: Serve from the project root so `index.html` and assets load correctly.

---

## Publish to GitHub Pages (web upload - easiest)
1. Create a new repository on GitHub named `giftforjoysree`.
2. On the repo page choose **Add file → Upload files**.
3. Drag-and-drop the project files (extract `giftforjoysree_full.zip` first if you prefer) so that `index.html` sits at the repository root.
4. Commit changes.
5. The included GitHub Actions workflow (in `.github/workflows/deploy.yml`) will automatically publish the site to:

   ```text
   https://<your-github-username>.github.io/giftforjoysree
   ```

6. Check the **Actions** tab to watch the publish job; when it succeeds, open the Pages link shown in the repository **Pages** settings.

Important notes:
- Make sure `index.html` is at the repository root (not inside a nested folder). If you upload a ZIP file directly to the repo, extract it locally first and upload the extracted files.
- A `.nojekyll` file is included so GitHub Pages will serve all files as-is.

---

## Publish via Git (command-line)
If you prefer using Git locally, run these commands from the project folder:

```bash
# If this folder is not already a git repo
git init
git branch -M main
git add -A
git commit -m "Prepare site for GitHub Pages"
# Create a repo on GitHub named 'giftforjoysree' and paste your repo URL below
git remote add origin https://github.com/<avro0820>/giftforjoysree.git
git push -u origin main
```

After the push, check the **Actions** tab and the **Pages** settings for the live URL.

---

## ZIP files included
- `giftforjoysree.zip` — working site (smaller, intended as deployable site archive)
- `giftforjoysree_full.zip` — complete project archive including README, workflow, and all assets (use this if you want everything together)

If you upload the ZIP to GitHub, extract it locally and upload the extracted files (GitHub does not serve files directly from a ZIP).

---

## Troubleshooting & tips
- 404 or "Page not found": verify `index.html` is in the repo root and that the Pages workflow ran successfully.
- Workflow issues: open **Actions ➜ Deploy to GitHub Pages** and view the logs for the failing step.
- Missing images or broken layout: make sure image files are uploaded to the repo and referenced by the correct filename.

---

## Need help?
- Reply **Push for me** if you want me to push this repository to GitHub for you (I will need a short-lived GitHub PAT with repo/workflow access if you prefer me to push), or
- Reply **Show me how** and I’ll give step-by-step screenshots and commands tailored for your system.


If you'd like, I can also update this README to include your GitHub username and the exact Pages URL once you give it to me.
