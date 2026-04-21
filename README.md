# MindByTWC — Productivity System Finder

## Deploy to Vercel in 3 steps

### Option A: Drag & Drop (Fastest)
1. Go to vercel.com → Log in → "Add New Project"
2. Choose "Deploy from template" → drag the `mindbytwc` folder
3. Click Deploy — live in ~30 seconds

### Option B: GitHub (Recommended for updates)
1. Push this folder to a GitHub repo
2. Go to vercel.com → "Add New Project" → Import from GitHub
3. Select the repo → Deploy

### Embedding in your existing MindByTWC website
Add this to any page on your site:
\`\`\`html
<iframe
  src="https://your-vercel-url.vercel.app"
  width="100%"
  height="900px"
  frameborder="0"
  style="border-radius: 8px;"
></iframe>
\`\`\`

Or link to it as a standalone page from your nav.

## Updating the Calendly link
In index.html, find line:
\`const CALENDLY = "https://calendly.com/thewellbeingcognoscente";\`
Replace the URL with any specific session type link from your Calendly.

## Files
- index.html — The full app (single file, no build step needed)
- vercel.json — Vercel routing config
- public/logo.png — Original logo (already embedded in index.html)
