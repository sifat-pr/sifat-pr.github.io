# Sifat Cybersecurity Portfolio Website

A modern, responsive dark-themed cybersecurity portfolio built with **raw HTML, CSS (Tailwind), and JavaScript**.

## 📁 Project Structure

```
stitch_sifat_cybersecurity_portfolio/
├── index.html              # Home page - Hero & expertise overview
├── portfolio.html          # Portfolio - Project showcase (Bento grid)
├── services.html           # Services - Security service offerings
├── certificates.html       # Certificates - Credential verification
├── contact.html            # Contact - Contact form & info
├── assets/
│   ├── images/             # All page images (locally downloaded)
│   │   ├── sifat-hero.png
│   │   ├── network-dashboard.png
│   │   ├── server-room-services.png
│   │   ├── server-room-portfolio.png
│   │   └── server-room-certificates.png
│   ├── css/                # Custom CSS (ready for future styles)
│   └── js/                 # Custom JavaScript (ready for future scripts)
├── certificates/           # Folder for user certificates (to populate later)
└── README.md              # This file
```

## 🎨 Design Features

- **Dark Theme**: Professional cybersecurity aesthetic with teal (#38debb) accent color
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Material Design Icons**: Clean UI with Material Symbols
- **Typography**: Space Grotesk (headlines) + Inter (body)
- **Advanced CSS**: Gradients, animations, and hover effects
- **No Dependencies**: Pure HTML/CSS/JavaScript (CDN-based Tailwind only)

## 🔗 Navigation

Each page is independently accessible:
- **Home** (`index.html`) - Landing page with core expertise
- **Services** (`services.html`) - Service offerings  
- **Portfolio** (`portfolio.html`) - Project showcase
- **Certificates** (`certificates.html`) - Credential verification
- **Contact** (`contact.html`) - Contact form

Navigation bar appears on all pages for seamless browsing.

## 📸 Images

All images are **locally downloaded** from Google's AI-generated image URLs:
- These are served from `./assets/images/` for reliable hosting on GitHub Pages
- No external image dependencies (faster loading, better reliability)

## 🚀 Deployment

### Local Testing
Simply open `index.html` in a web browser. All pages reference each other with relative links.

### GitHub Pages Deployment with GitHub Actions

#### **Automatic Deployment Workflow (Recommended)**

This repository includes automated GitHub Actions workflow for continuous deployment.

**Setup (One-time):**
1. Push to your GitHub repository
2. Go to repository **Settings** → **Pages**
3. Under "Build and deployment", select **Source: GitHub Actions**
4. The workflow will automatically run on every push

**How it works:**
- Event: You push code to `main` branch
- Action: GitHub Actions automatically builds and deploys
- Result: Site live at `https://yourusername.github.io/`

**Deployment Process:**
```bash
# Make changes to your files
git add .
git commit -m "Update portfolio"
git push origin main

# ✅ Automatic deployment starts!
# Check progress: GitHub repository → Actions tab
```

**Monitor Deployment:**
1. Go to repository → **Actions** tab
2. Click the latest workflow run
3. Watch status: 🟡 Running → 🟢 Completed

**Deployment Timeline:**
- Push to GitHub: ~5 seconds
- Workflow triggers: ~10 seconds  
- Deploy to Pages: ~30 seconds
- **Total: ~1 minute to live**

#### **Direct GitHub Pages (Manual)**
Alternative if you don't want GitHub Actions:
1. Push this folder to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Set the source to "Deploy from a branch"
4. Access your site at `https://yourusername.github.io/repo-name/`

### Internet Hosting
Works on any standard web hosting with no special requirements:
- No backend server needed
- No databases
- No build process required
- Pure static HTML/CSS

### Workflow File Location
GitHub Actions configuration is in: `.github/workflows/deploy.yml`

**What it does:**
- ✅ Triggered on every push to `main` branch
- ✅ Uploads all repository files
- ✅ Deploys to GitHub Pages automatically
- ✅ Shows deployment URL in Actions summary
- ✅ Handles all permissions automatically

## 🛠️ Future Enhancements

### Ready-to-Add Features
- `/assets/css/custom.css` - For additional custom styling
- `/assets/js/main.js` - For interactive features (animations, form validation, etc.)
- `/certificates/` - Add your certification files/images here

### Suggested Improvements
1. **Form Handling**: Add backend service for contact form (Formspree, Netlify Forms, etc.)
2. **Analytics**: Add Google Analytics or Plausible Analytics script
3. **Dark/Light Mode Toggle**: Add theme switcher JavaScript
4. **Mobile Menu**: Add hamburger menu for smaller screens
5. **Animations**: Add Intersection Observer for scroll animations
6. **Blog/Articles**: Add a blog section with markdown support

## 📋 Browser Compatibility

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile**: iOS Safari, Android Chrome
- **Tailwind CSS**: Requires browsers supporting:
  - CSS Grid
  - Flexbox
  - CSS Custom Properties
  - Backdrop filters

## 🔐 Security Notes

- All transmission forms can be connected to backend services
- No sensitive data stored in HTML/JavaScript (client-side only)
- Ready for integration with email services, CRM systems, etc.

## 📄 License

This portfolio website is open source and available for personal and commercial use.

## ✨ Credits

Built with:
- **Tailwind CSS** - Utility-first CSS framework (CDN)
- **Google Fonts** - Space Grotesk & Inter typefaces
- **Material Symbols** - Icon library
- **HTML5** & **CSS3** - Modern web standards

---

**Last Updated**: April 15, 2026  
**Version**: 1.0.0  
**Status**: Production Ready ✅

For questions or updates, contact through the Contact page.
