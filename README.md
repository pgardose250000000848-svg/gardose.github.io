# Pearl Kristian M. Gardose - Professional Portfolio

A premium, professional portfolio website showcasing enterprise-level software engineering projects with a sophisticated bento grid layout, polished micro-interactions, and modern UI/UX design.

🌐 **Live Demo**: [Add your GitHub Pages URL here after deployment]

---

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Click "Sign up"
3. Follow the registration process

### Step 2: Create a New Repository
1. Click the **"+"** icon in the top-right corner
2. Select **"New repository"**
3. Repository name: `portfolio` (or any name you prefer)
4. Description: "Professional portfolio showcasing my software engineering projects"
5. Set to **Public** (required for free GitHub Pages)
6. ✅ Check **"Add a README file"** (optional)
7. Click **"Create repository"**

### Step 3: Upload Your Portfolio File
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop your `index.html` file
3. Scroll down and click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to repository **Settings** (gear icon in top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **"Save"**
5. Wait 1-2 minutes for deployment
6. Your site will be live at: `https://yourusername.github.io/portfolio/`

### Step 5: Optional - Use Custom Domain
1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In GitHub Pages settings, add your custom domain
3. Configure DNS settings with your domain provider
4. Enable **"Enforce HTTPS"**

---

## 📋 Pre-Deployment Checklist

Before deploying, make sure to update these sections in `index.html`:

### ✏️ Required Updates

1. **Email Address** (Line ~398):
```javascript
const email = 'pearl.gardose@example.com'; // Change to your real email
```

2. **Social Media Links** (Lines ~375-383):
```html
<a href="https://github.com/YOUR-USERNAME" ...>
<a href="https://linkedin.com/in/YOUR-USERNAME" ...>
<a href="https://twitter.com/YOUR-USERNAME" ...>
```

3. **Project Links** (Throughout projects section):
- Replace `https://github.com` with your actual project repositories
- Replace `#` in "Live Demo" with actual deployment URLs

4. **Project Images** (Optional):
- Replace Unsplash URLs with actual project screenshots
- Upload images to repository and use relative paths

5. **Project Descriptions**:
- Customize the 6 project descriptions to match your real work
- Add specific metrics and technologies you've used

---

## 🎨 Features

### Visual Design
- **Premium Dark Theme**: Sophisticated Zinc palette (#09090b background)
- **Professional Typography**: Inter font with optimized spacing
- **Indigo Accents**: Strategic use of #6366f1 for CTAs
- **Real Project Images**: Integrated with Unsplash API
- **Glassmorphism**: Modern glass-effect cards with backdrop blur

### Micro-Interactions
- ✨ Smooth scroll-reveal animations
- 🎯 Card hover effects with scale & glow
- 💫 Button ripple effects
- 🖼️ Image zoom on hover
- 📊 Infinite scrolling tech stack marquee
- 🔗 Animated link underlines

### Sections
1. **Hero** - Professional introduction with availability status
2. **Tech Stack** - Scrolling marquee of technologies
3. **Projects** - 6 enterprise-level project showcases
4. **Philosophy** - Professional mission statement
5. **Contact** - Social links + one-click email copy

---

## 💻 Technologies Used

- HTML5
- CSS3 (with custom animations)
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)

---

## 🛠️ Customization Guide

### Change Colors
```css
/* In <style> section, update: */
.accent { color: #YOUR-COLOR; }
.accent-bg { background-color: #YOUR-COLOR; }
```

### Add More Projects
1. Find the projects section (line ~128)
2. Copy any project card `<div class="glass p-6 rounded-2xl">...</div>`
3. Paste below existing projects
4. Update content and links

### Modify Tech Stack
1. Find the marquee section (lines ~72-95)
2. Add/remove `<span>` elements
3. Update icons from [Font Awesome](https://fontawesome.com/icons)

---

## 📱 Responsive Design

- **Mobile**: < 640px (Single column)
- **Tablet**: 640px - 1024px (Two columns)
- **Desktop**: 1024px+ (Three columns)

All touch targets optimized for mobile (minimum 56px).

---

## 🔧 Alternative Deployment Methods

### Netlify (Easiest)
1. Go to [netlify.com](https://www.netlify.com/)
2. Drag and drop your `index.html` file
3. Get instant live URL
4. Free custom domain support

### Vercel
1. Go to [vercel.com](https://vercel.com/)
2. Import from GitHub repository
3. Deploy automatically
4. Get production URL

### Traditional Web Hosting
1. Purchase hosting (Bluehost, SiteGround, etc.)
2. Use cPanel or FTP to upload `index.html`
3. Access via your domain

---

## 📊 Performance Optimizations

- ✅ Single-file architecture (no build process)
- ✅ CDN resources for fast loading
- ✅ Lazy loading images
- ✅ Optimized fonts with display=swap
- ✅ Hardware-accelerated CSS animations
- ✅ Minimal JavaScript for maximum performance

---

## ♿ Accessibility Features

- Semantic HTML5 structure
- ARIA labels on icon-only links
- Keyboard navigation support
- WCAG AA color contrast compliance
- Screen reader friendly

---

## 📞 Support & Contact

**Pearl Kristian M. Gardose**
- 📧 Email: pearl.gardose@example.com
- 💼 LinkedIn: [linkedin.com/in/pearlgardose](https://linkedin.com/in/pearlgardose)
- 🐙 GitHub: [github.com/pearlgardose](https://github.com/pearlgardose)

---

## 📝 License

This portfolio is free to use for personal purposes. Feel free to customize it for your own use.

---

## 🎯 Post-Deployment Tips

### 1. Test Your Site
- ✅ Check all links work
- ✅ Test on mobile devices
- ✅ Verify email copy function
- ✅ Test in different browsers (Chrome, Firefox, Safari)

### 2. Share Your Portfolio
- Add URL to LinkedIn profile
- Include in email signature
- Share on Twitter/social media
- Add to resume/CV

### 3. Keep It Updated
- Add new projects as you complete them
- Update tech stack as you learn new technologies
- Refresh project screenshots
- Update availability status

### 4. Track Visitors (Optional)
Add Google Analytics:
```html
<!-- Before </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-TRACKING-ID');
</script>
```

### 5. SEO Optimization
- Update meta description with keywords
- Add Open Graph tags for social sharing
- Submit sitemap to Google Search Console
- Get backlinks from LinkedIn, GitHub profile

---

## 🚨 Troubleshooting

### Site not showing after deployment?
- Wait 2-3 minutes for GitHub Pages to build
- Check that file is named `index.html` (lowercase)
- Verify repository is set to Public
- Clear browser cache and try again

### Images not loading?
- Check Unsplash URLs are correct
- Replace with uploaded images if Unsplash is blocked
- Ensure image paths are correct

### Styles look broken?
- Verify Tailwind CDN link is working
- Check browser console for errors
- Try different browser

### Email copy not working?
- Ensure you're on HTTPS (not HTTP)
- Try different browser
- Check JavaScript console for errors

---

## 🎓 Learn More

Want to enhance your portfolio further?

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Web Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

---

## 🌟 Credits

**Designed & Developed by:** Pearl Kristian M. Gardose  
**Built with:** HTML, CSS, Tailwind CSS, JavaScript  
**Icons:** Font Awesome  
**Fonts:** Google Fonts (Inter)  
**Images:** Unsplash Source API

---

**Last Updated:** February 2026

---

## 💡 Next Steps

1. ✅ Customize all personal information
2. ✅ Add your real project links and descriptions
3. ✅ Upload to GitHub
4. ✅ Enable GitHub Pages
5. ✅ Share your portfolio URL with the world!

**Your portfolio URL will be:**  
`https://YOUR-GITHUB-USERNAME.github.io/portfolio/`

Good luck with your job search and career! 🚀
