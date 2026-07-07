# How to Update This Website

Your site lives at: https://shashipratap1998.github.io
It is just one file: `index.html`. To update the site, you replace that file with a new version and push it to GitHub. Changes go live automatically within 1-2 minutes.

There are two ways to do this. Use Option A if you're not near this computer or don't want to use the terminal. Use Option B if you're on this computer.

## Option A: Update from any computer/phone, no terminal needed

1. Make your new page (e.g. re-export from Claude Design, or ask Claude to edit it for you). Save it as `index.html`.
2. Go to https://github.com/shashipratap1998/shashipratap1998.github.io
3. Click on `index.html` in the file list.
4. Click the pencil icon (Edit) in the top right — or click the trash icon to delete it first, then click "Add file" > "Upload files" to upload the new one.
   - Easiest path: click "Add file" > "Upload files" > drag in your new `index.html` > it will ask to replace the existing file > confirm.
5. Scroll down, add a short message like "update site", click "Commit changes".
6. Wait 1-2 minutes, then refresh https://shashipratap1998.github.io to see it live.

## Option B: Update from this computer (using Claude Code or terminal)

The website files are kept in this folder: `~/shashipratap1998.github.io`

1. Put your new `index.html` into that folder, replacing the old one.
2. Open a terminal in that folder and run:
   ```
   git add index.html
   git commit -m "update site"
   git push
   ```
3. Wait 1-2 minutes, then refresh https://shashipratap1998.github.io to see it live.

If you're asking Claude Code to do this for you, just say something like: "I have a new index.html in Downloads, please update my website with it" — Claude can copy it into `~/shashipratap1998.github.io` and push it for you.

## Notes

- The site is a single self-contained `index.html` file exported from Claude Design (Bundled Page format) — all styling and content is packed into that one file, so you generally don't need any other files.
- GitHub Pages is already enabled for this repo automatically because the repo name matches `<username>.github.io`. No extra setup needed.
- If the site doesn't update after a few minutes, check the "Actions" tab on the GitHub repo page for a red X, which would indicate a build error.
