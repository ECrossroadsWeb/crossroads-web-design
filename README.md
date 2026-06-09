# Crossroads Web Design — Website

A static, self-contained website (no build step, no dependencies). Each page is a
single HTML file with its CSS and images embedded inline, so it works anywhere you
host it.

## Files
- `index.html` ............ Main Crossroads Web Design site (home/portfolio/packages/contact)
- `home-services.html` .... Demo: Summit Home Services
- `food-truck.html` ....... Demo: Switchback Street Eats
- `corporate.html` ........ Demo: Meridian Global
  (All four are cross-linked. `index.html` is the home page.)

## Deploy with GitHub + Vercel (quick version)
1. Create a new GitHub repository (e.g. `crossroads-web-design`).
2. Upload all four `.html` files (and this README) to the repo root.
3. At vercel.com, sign in with GitHub → "Add New… → Project" → import the repo.
4. Framework Preset: "Other". Leave Build Command / Output empty. Click "Deploy".
5. Your site is live at `https://<project>.vercel.app`. Add a custom domain in
   Project → Settings → Domains.

DNS for a custom domain (set these at your domain registrar):
- Apex (example.com):     A     record →  76.76.21.21
- www (www.example.com):  CNAME record →  (use the exact value Vercel shows you)

## Notes
- Contact: ethan@crossroadswebdesign.com · +1 (801) 232-5459
- The quote form opens the visitor's email app pre-addressed to your email
  (mailto). No server required. A form service (e.g. Formspree) can be added later
  if you want submissions captured automatically.
- Vercel's free "Hobby" plan is for non-commercial use; a business site requires
  the Pro plan. See the chat notes for free commercial-friendly alternatives.
- Demo photos are placeholders from free/template sources — swap for the client's
  own or licensed images before using a demo as a real live site.
