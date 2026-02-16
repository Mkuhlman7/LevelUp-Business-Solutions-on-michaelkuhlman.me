# LevelUp Business Solutions - Landing Page

AI Consulting landing page for michaelkuhlman.me

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g., `levelup-site` or `michaelkuhlman.me`)
2. Push this code:

```bash
cd ai-consulting-site
git init
git add .
git commit -m "Initial landing page"
git branch -M main
git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

3. Go to **Settings → Pages → Source** → select `main` branch → Save
4. GitHub Pages will be live in ~60 seconds

## Connect Custom Domain

### In GitHub:
- **Settings → Pages → Custom domain** → type `michaelkuhlman.me` → Save
- Check "Enforce HTTPS"

### At your domain registrar (DNS settings):
Add these **A records** pointing to GitHub Pages:

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | YOUR_USERNAME.github.io |

DNS propagation takes 5-30 minutes. HTTPS certificate is automatic.

## TODO After Deploy
- [ ] Sign up for Calendly (free) and replace the mailto: link with your Calendly URL
- [ ] Verify the "10+ years" number in the credibility section is accurate
- [ ] Add Google Analytics (optional)
