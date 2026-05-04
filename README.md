# 🌙 Sleepy Hollow - Discord Server Landing Page

A beautiful, spooky landing page for the Sleepy Hollow horror-themed Discord community server.

## ✨ Features

- **Dark & Light Mode Toggle** - Theme preference is saved in browser
- **Fully Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Professional UI** - Smooth animations, hover effects, and gradient accents
- **SEO Optimized** - Meta descriptions, keywords, and Open Graph tags
- **Social Media Ready** - Shareable with proper Open Graph and Twitter Card tags
- **Favicon** - Custom moon emoji favicon in browser tab
- **Analytics Ready** - Google Analytics integration for tracking

## 🚀 Getting Started

### Local Development
```bash
python3 -m http.server 8000
# Visit http://localhost:8000 in your browser
```

### Files
- `index.html` - Main HTML file with all content
- `styles.css` - Complete styling with light/dark mode support

## 📊 Setting Up Google Analytics

To enable visitor tracking:

1. Go to [Google Analytics](https://analytics.google.com)
2. Create a new property for your website
3. Get your Measurement ID (starts with `G-`)
4. Replace `G-XXXXXXXXXX` in `index.html` (lines in the Analytics script) with your ID

Example:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-YOUR-ID-HERE"></script>
```

## 🎨 Customization

### Discord Invite Link
Update the Discord invite URL in `index.html`:
```html
<a href="https://discord.gg/YOUR-INVITE-CODE" ...>
```

### Colors & Theme
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-dark: #0a0e27;
    --accent-purple: #8b5fbf;
    --accent-orange: #ff6b35;
}
```

### Domain Setup
Update the Open Graph URL in `index.html`:
```html
<meta property="og:url" content="https://your-domain.com">
```

## 🌐 Hosting on GitHub Pages

1. Push your code to GitHub:
```bash
git add .
git commit -m "Add Sleepy Hollow website"
git push
```

2. Go to repository Settings → Pages
3. Select `main` branch as source
4. GitHub Pages will provide your URL

## 📱 SEO & Social Media

The website includes:
- ✅ Meta description for search engines
- ✅ Keywords for better SEO
- ✅ Open Graph tags (Facebook, LinkedIn, etc.)
- ✅ Twitter Card tags
- ✅ Responsive mobile design

When you share the link on social media, it will show a preview with the title, description, and image!

## 🔧 Optional Enhancements

- Add actual favicon image (replace the SVG data URI)
- Custom domain from Namecheap, GoDaddy, or similar
- Email subscription form
- Member testimonials section
- Photo gallery or video background

---

**Made with 🌙 for Sleepy Hollow Community**
