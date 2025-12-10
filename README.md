# Lunio Landing Page

Simple landing page for Lunio - Client Management Made Simple

## GitHub Pages Setup

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Select source: "Deploy from a branch"
4. Select branch: `main` (or `master`)
5. Select folder: `/ (root)`
6. Click Save
7. Your site will be available at: `https://[your-username].github.io/lunio-landing/`

## Custom Domain (Optional)

If you want to use a custom domain like `lunio.app`:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update the domain in GitHub Pages settings

## Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

Then visit `http://localhost:8000`

