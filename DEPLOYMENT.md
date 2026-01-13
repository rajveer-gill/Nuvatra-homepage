# Deployment Notes

## Current Setup

### Domain Management
- **Provider**: Squarespace
- **Domain**: nuvatrahq.com
- **DNS Management**: Handled through Squarespace dashboard

### Hosting
- **Provider**: Netlify
- **Repository**: https://github.com/rajveer-gill/Nuvatra-homepage
- **Auto-deploy**: Enabled (deploys automatically on git push)

### Email Service
- **Provider**: EmailJS
- **Configuration**: Stored in `config.js`
- **Email Destination**: info@nuvatrahq.com

## Deployment Workflow

1. **Make changes locally**
2. **Commit and push to GitHub**:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin master
   ```
3. **Netlify automatically deploys** (usually takes 1-2 minutes)
4. **Site is live** at nuvatrahq.com

## Important Links

- **GitHub Repository**: https://github.com/rajveer-gill/Nuvatra-homepage
- **Netlify Dashboard**: https://app.netlify.com
- **Squarespace Domain Settings**: Manage through Squarespace dashboard
- **EmailJS Dashboard**: https://dashboard.emailjs.com

## DNS Configuration

The domain `nuvatrahq.com` is managed through Squarespace and points to Netlify. DNS records should be configured in Squarespace to point to Netlify's servers.

## Troubleshooting

### If site doesn't update after push:
1. Check Netlify dashboard for deployment status
2. Verify GitHub repository has latest changes
3. Check Netlify build logs for errors

### If domain doesn't resolve:
1. Check DNS settings in Squarespace
2. Verify Netlify custom domain configuration
3. Allow 24-48 hours for DNS propagation

### If contact form doesn't work:
1. Verify EmailJS credentials in `config.js`
2. Check EmailJS dashboard for service status
3. Verify EmailJS template is configured correctly

## Notes

- All changes should be committed to GitHub
- Netlify automatically builds and deploys from the `master` branch
- EmailJS credentials are safe to be public (designed for client-side use)
- Domain renewal is managed through Squarespace
