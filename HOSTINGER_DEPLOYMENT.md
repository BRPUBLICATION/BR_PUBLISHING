# BR Publishing House - Hostinger Deployment Guide

## Files Ready for Upload
Your website is now optimized for Hostinger hosting. Here are the files you need to upload:

### Core Files:
- `index.html` - Main homepage
- `.htaccess` - Server configuration and security
- `CNAME` - Custom domain configuration (if using custom domain)

### Book Pages:
- `ai-driven-data-engineering.html`
- `ai-financial-book.html`
- `cloud-native-architecture.html`
- `cognitive-cloud-delivery.html`
- `digital-operations.html`
- `from-data-to-dossier.html`
- `gen-ai-book.html`
- `intelligent-automation.html`
- `intelligent-cloud-migration.html`
- `micro.html`
- `mulesoft.html`
- `plug-and-play.html`
- `privacy-first-logistics.html`
- `smart-cloud.html`
- `zero-touch-cloud-networking.html`

## Step-by-Step Hostinger Deployment

### 1. Access Hostinger Control Panel
1. Log into your Hostinger account
2. Go to your hosting control panel (hPanel)

### 2. Upload Files via File Manager
1. Navigate to **File Manager** in hPanel
2. Go to `public_html` folder (this is your website root)
3. Delete any default files (like index.html, if present)
4. Upload all your HTML files and the `.htaccess` file

### 3. Upload via FTP (Alternative Method)
1. Use an FTP client like FileZilla
2. Connect using your Hostinger FTP credentials
3. Upload all files to the `public_html` directory

### 4. Set Up Custom Domain (Optional)
1. In hPanel, go to **Domains**
2. Add your custom domain
3. Point your domain's nameservers to Hostinger
4. Update the `CNAME` file if needed

### 5. Enable SSL Certificate
1. In hPanel, go to **SSL**
2. Enable the free SSL certificate
3. Force HTTPS redirect (already configured in .htaccess)

### 6. Test Your Website
1. Visit your domain to test the homepage
2. Check all book pages are accessible
3. Verify mobile responsiveness
4. Test contact forms and navigation

## Post-Deployment Checklist
- [ ] All pages load correctly
- [ ] Navigation works properly
- [ ] Mobile responsive design
- [ ] SSL certificate active
- [ ] Contact forms functional
- [ ] Page loading speed acceptable
- [ ] SEO meta tags present

## Troubleshooting
- If pages don't load: Check file permissions (should be 644 for files, 755 for folders)
- If .htaccess doesn't work: Ensure mod_rewrite is enabled on your hosting plan
- If SSL issues: Contact Hostinger support to enable SSL

## Performance Tips
- The .htaccess file includes compression and caching rules
- All external resources (fonts, icons) are loaded from CDNs
- Images are optimized for web delivery

Your website is now ready for Hostinger hosting!

