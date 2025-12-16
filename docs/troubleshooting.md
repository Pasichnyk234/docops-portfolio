# Troubleshooting

## Symptom: GitHub Pages shows only a blank/simple page
**Possible cause:** Pages is publishing the wrong source (e.g., root of main branch).  
**Fix:**
1. Go to **Settings → Pages**
2. Set source to **Deploy from a branch**
3. Select **Branch: gh-pages** and folder **/(root)**
4. Save and refresh the site (Ctrl+F5)

## Symptom: Changes don’t appear on the site
**Possible cause:** caching or deployment still running.  
**Fix:** open in Incognito / Ctrl+F5 and check **Actions** status.
