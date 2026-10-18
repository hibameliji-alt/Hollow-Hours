# The Mystery Files

A browser mystery game with 1,000 procedurally generated cases. No build step, no dependencies: it's one `index.html`.

## Play
Pick an investigator, walk the house (tap a tile or use the arrows), and question each suspect. Everyone tells the truth except one guest, who lied about where they were at the time of the murder. Compare the answers, find the one that doesn't match, and accuse.

- 4 investigators, each with a different perk
- 1,000 cases; solving one unlocks the next
- Harder cases add more suspects, more rooms, more furniture, and fewer questions
- Progress saves in your browser (localStorage)

## Run locally
Open `index.html` in a browser.

## Publish on GitHub Pages
1. Create a repo and add `index.html` and `README.md`.
2. Go to Settings → Pages.
3. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. Your game goes live at `https://<your-username>.github.io/<repo-name>/`.
