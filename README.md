# Bar Menu Website

This repository hosts the menu for [Your Bar Name] using GitHub Pages.

## Setup Instructions

1. Upload your menu PDF file as `menu.pdf` in the root directory
2. Enable GitHub Pages in your repository settings:
   - Go to Settings > Pages
   - Under "Source", select "main" branch
   - Click "Save"

## Custom Domain Setup

1. Purchase a domain name from a domain registrar (e.g., GoDaddy, Namecheap)
2. In your domain registrar's settings, add these DNS records:
   ```
   Type: A
   Name: @
   Value: 
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
3. Add a CNAME record:
   ```
   Type: CNAME
   Name: www
   Value: [your-username].github.io
   ```
4. In your GitHub repository:
   - Go to Settings > Pages
   - Under "Custom domain", enter your domain
   - Check "Enforce HTTPS"
   - Click "Save"

Your menu will be available at:
- `https://yourdomain.com/menu.pdf`
- `https://www.yourdomain.com/menu.pdf` 