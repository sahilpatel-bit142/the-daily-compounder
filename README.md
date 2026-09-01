# The Daily Compounder — V5

## What changed from V4

- Removed the experimental **WRITE** link from the public navigation.
- Removed the local Writer's Desk from the public build.
- Kept the reader-facing publication pages:
  - Home
  - Research
  - Reads
  - Blogs
  - Articles
  - About
  - Individual article pages
- Prepared the project as a simple static site for GitHub + Netlify.

## Preview locally

From this folder in PowerShell:

    py -m http.server 8000

Then open:

    http://localhost:8000

Keep PowerShell running while previewing.

## What happens next

### Step 1 — GitHub
Create a GitHub repository and upload this folder's files.

### Step 2 — Netlify
Connect the GitHub repository to Netlify. Netlify will publish the site.

### Step 3 — Test the live site
Netlify gives you a temporary public address ending in `.netlify.app`.

### Step 4 — Custom domain
Later, connect a domain such as `thedailycompounder.com` if you choose to buy one.

### Step 5 — CMS
Only after the website is live do we add the private CMS.

Final publishing flow:

    YOU
      ↓
    CMS
      ↓
    Publish
      ↓
    GitHub
      ↓
    Netlify
      ↓
    LIVE WEBSITE

The CMS is not part of V5 yet. That is intentional: V5 first gets the website online cleanly.
