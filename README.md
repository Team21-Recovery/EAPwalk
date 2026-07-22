# Team21 EAP Field Intake

A mobile-friendly field tool for gathering Emergency Action Plan intake data during on-site
campus walkthroughs — venues, AED/equipment locations, gate keys, entrances, and a printable
PDF summary.

## Get a permanent URL (no coding required)

### Step 1 — Put this project on GitHub
1. Go to [github.com](https://github.com) and create a free account if you don't have one.
2. Click the **+** in the top right → **New repository**. Name it `team21-eap` (or anything).
   Keep it Public or Private, doesn't matter. Click **Create repository**.
3. On the new repo's page, click **uploading an existing file**.
4. Drag in every file from this project (including the `src` folder) and click **Commit changes**.

### Step 2 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign up (use "Continue with GitHub" — fastest).
2. Click **Add New... → Project**.
3. Select the `team21-eap` repo you just created.
4. Vercel auto-detects this is a Vite project — leave all settings as default.
5. Click **Deploy**. Wait ~60 seconds.
6. You'll get a live URL like `https://team21-eap.vercel.app` — that's your permanent link.
   Bookmark it, or "Add to Home Screen" on your phone so it opens like an app.

### Making changes later
Edit files directly on GitHub (or re-upload updated files the same way you did in Step 1) —
Vercel automatically re-deploys within a minute of any change to the repo.

## Notes
- Data is saved locally in the browser (per device) using `localStorage`, so each device/browser
  keeps its own walkthrough data. Use "Export PDF" or "Copy Summary" to move data off a device.
- No backend, database, or ongoing cost — Vercel's free tier covers this comfortably.

## Local development (optional, for developers)
```
npm install
npm run dev
```
