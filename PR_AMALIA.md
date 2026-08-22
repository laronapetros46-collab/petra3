# PR Title: amalia

## Summary
Move the site files from the Petra/ subfolder to the repository root so GitHub Pages can publish the site from the default branch.

## Changes included on this branch (move-site-to-root)
- index.html (moved from Petra/index.html)
- style1.css (moved from Petra/style1.css)
- index.js (moved from Petra/index.js)
- seasons.html (moved from Petra/seasons.html)
- seasons-of-the-soul.css (moved from Petra/seasons-of-the-soul.css)
- seasons-of-the-soul.js (moved from Petra/seasons-of-the-soul.js)
- Petra/library.jpg → images/library.jpg (moved)
- .nojekyll (added to publishing root to disable Jekyll)

## Notes for reviewer
- I moved files only (preserved content). Links in HTML are relative and should continue to work after merge.
- Please review any absolute links that referenced the Petra/ prefix (none were found in the main files but double-check).
- If the repository has branch protection or required checks, merge may require approvals — follow org rules.

## Verification steps (after merge)
1. Wait a few minutes for GitHub Pages to build.
2. Visit: https://laronapetros46-collab.github.io/petra3/
3. If the page looks broken, check `Settings → Pages` for build errors and inspect the Files changed tab in this PR for missing path updates.

## Post-merge cleanup
- Optionally delete branch: move-site-to-root

---

If you want any changes to the PR title or description, tell me now and I will update this file on the branch.