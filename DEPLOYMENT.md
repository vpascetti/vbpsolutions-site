# GitHub Pages Deployment Instructions

## Quick Setup

1. **Create GitHub Repository**
   - Create new repository named `vbpsolutions-website`
   - Make it public (required for GitHub Pages on free plan)

2. **Upload Files**
   - Upload all files from the `github-deploy` folder to your repository
   - Ensure CNAME file is included for custom domain

3. **Configure GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main (or master)
   - Folder: / (root)
   - Save settings

4. **Domain Configuration**
   - Your CNAME file points to: `vbpsolutions.net`
   - Configure DNS A records to point to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

## File Structure
```
github-deploy/
├── index.html          # Main website file
├── assets/             # CSS and JavaScript bundles
├── CNAME              # Custom domain configuration
├── .nojekyll          # Disable Jekyll processing
├── 404.html           # Custom 404 error page
├── README.md          # Repository documentation
└── .gitignore         # Git ignore rules
```

## Features Included
- Responsive design for all devices
- Working contact form (Formspree integration)
- Custom 404 error page
- SEO optimization
- Performance optimized assets

## Contact Form
- Configured to send emails to: vpascetti@vbpsolutions.net
- Uses Formspree endpoint: movwjojg
- No backend required

## Support
For issues, contact vpascetti@vbpsolutions.net