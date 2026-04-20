# Deployment Guide

## GitHub Repository
**URL:** https://github.com/divergentsolutions2026-bit/divergent-solutions-website

## Enable GitHub Pages

### Manual Setup:
1. Go to: https://github.com/divergentsolutions2026-bit/divergent-solutions-website/settings/pages
2. Under "Source", select "Deploy from a branch"
3. Select "master" branch
4. Select "/ (root)" folder
5. Click "Save"
6. Wait a few minutes for deployment

### Expected GitHub Pages URL:
https://divergentsolutions2026-bit.github.io/divergent-solutions-website/

## Alternative Deployment Options

### Netlify (Recommended for custom domain):
1. Go to https://netlify.com
2. Drag and drop the `agency-website` folder
3. Or connect GitHub repository
4. Automatic deployment on push

### Vercel:
1. Go to https://vercel.com
2. Import GitHub repository
3. Automatic deployment

## Custom Domain Setup

### For GitHub Pages:
1. Buy domain from Namecheap, GoDaddy, etc.
2. Add CNAME record pointing to `divergentsolutions2026-bit.github.io`
3. In GitHub Pages settings, add custom domain

### For Netlify/Vercel:
1. Connect custom domain in dashboard
2. Update DNS records as instructed

## Local Development

1. Clone repository:
   ```bash
   git clone https://github.com/divergentsolutions2026-bit/divergent-solutions-website.git
   ```

2. Open `index.html` in browser
3. Edit files as needed
4. Test changes locally

5. Commit and push:
   ```bash
   git add .
   git commit -m "Update description"
   git push origin master
   ```

## File Structure
```
divergent-solutions-website/
├── index.html          # Main website
├── css/style.css      # All styles
├── js/script.js       # Interactive features
├── README.md          # Documentation
└── assets/            # Images and icons
```

## Contact
For deployment issues, contact:
- Email: divergentsolutions2026@gmail.com
- GitHub: @divergentsolutions2026-bit