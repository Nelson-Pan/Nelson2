GITHUB METHOD (FREE) — SAME LAYOUT

What this does:
- Client page loads products from products.json
- Admin page edits products, then downloads a new products.json
- You upload/replace products.json in GitHub
- Netlify auto-deploys so everyone sees the update

FILES:
- index.html       (customer)
- admin.html       (admin editor)
- products.json    (your products database)

SETUP (GitHub + Netlify):
1) Create a GitHub account (free) and a new repo (public or private).
2) Upload the whole folder contents into the repo.
3) Netlify → Add new site → Import from Git
   - Connect to GitHub
   - Pick the repo
   - Deploy (no build settings needed)

HOW TO ADD PRODUCTS:
1) Open /admin.html on your Netlify site
2) Add product(s)
3) Click “Download products.json”
4) Go to GitHub repo → upload/replace products.json → Commit changes
5) Wait for Netlify to redeploy (usually seconds)
6) Customers refresh / and see it

NOTES:
- This is free and doesn’t expire.
- Updates are not instant like Firebase (they appear after Netlify redeploy).
- If you want true instant updates + login security, that needs a real backend account (Firebase/Supabase).
