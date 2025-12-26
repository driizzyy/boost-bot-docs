# Driizzyy Boost Bot V3 - Documentation

Professional documentation website for Driizzyy Boost Bot V3.

## Deployment Instructions

### GitHub Pages Setup

1. **Push to GitHub:**
   `ash
   git add docs/
   git commit -m "Add documentation website"
   git push origin main
   `

2. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch and "/docs" folder as source
   - Click Save

3. **Update Meta Tags:**
   Open docs/index.html and replace:
   - https://yourusername.github.io/BoostBotV3-main/ with your actual GitHub Pages URL
   - Update the og:image and 	witter:image URLs

4. **Add Assets:**
   Place your branding assets in docs/assets/:
   - icon.png - Your bot icon/logo (recommended: 512x512px)
   - anner.gif - Your banner image (recommended: 1200x630px for optimal Discord embeds)

5. **Access Your Site:**
   Your documentation will be available at:
   https://yourusername.github.io/repository-name/

## Features

-  Modern, responsive design
-  Professional Discord-themed styling
-  Mobile-friendly navigation
-  Full command reference
-  Complete setup guide
-  Smooth animations and interactions
-  SEO optimized with Open Graph meta tags
-  Discord embed support

## Customization

### Colors
Edit the CSS variables in docs/styles.css:
`css
:root {
    --primary-color: #00bfbf;
    --secondary-color: #7289da;
    --accent-color: #f47fff;
}
`

### Content
All content is in docs/index.html - edit sections as needed.

### Discord Link
Replace all instances of https://discord.gg/Tz5AueD9Ft with your actual Discord invite link.

## Local Testing

Open docs/index.html in your browser to test locally before deploying.

## Support

Join our Discord: https://discord.gg/Tz5AueD9Ft

---

 2025 Driizzyy Boosts Inc. All rights reserved.
