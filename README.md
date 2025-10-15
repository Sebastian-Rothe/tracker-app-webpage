# 🌐 Routine Tracker - Landing Page

A responsive, multilingual landing page for the Routine Tracker mobile app, showcasing features and providing download information.

## 🌟 Features

- **Responsive Design**: Optimized for all device sizes (mobile-first approach)
- **Multilingual Support**: German and English with dynamic language switching
- **SEO Optimized**: Meta tags, structured data, sitemap, and semantic HTML
- **Modern UI**: Clean design with Tailwind CSS, gradients, and smooth animations
- **Performance**: Fast loading with preloaded resources and optimized assets
- **Accessibility**: WCAG compliant with ARIA labels and keyboard navigation
- **Temporary Banner**: Easily removable "download not available" notices

## 🚀 Live Demo

**Website**: https://tracker-app-webpage.netlify.app/

## 📱 About the App

Routine Tracker is an intuitive Android habit tracking app featuring:

- ✅ **Multiple Routine Management**: Create unlimited daily habits
- 🔥 **Streak Tracking**: Build impressive consistency chains
- 🔔 **Smart Notifications**: Personalized reminders at perfect times
- 📊 **Detailed Analytics**: Progress trends and meaningful statistics
- 🏆 **Achievement System**: Gamification elements and milestone rewards
- 🔒 **Privacy-First**: 100% local storage, no cloud sync required
- 🌓 **Theme Support**: Automatic dark/light mode switching

## 🛠️ Tech Stack

- **HTML5**: Semantic markup with modern standards
- **Tailwind CSS 2.2.19**: Utility-first styling framework
- **Vanilla JavaScript**: Clean, dependency-free interactivity
- **Font Awesome 6**: Professional icons and symbols
- **Structured Data**: Schema.org markup for SEO
- **Netlify**: Hosting with automatic deployments

## 📁 Project Structure

```
tracker-app-webpage/
├── index.html              # Main landing page (multilingual)
├── datenschutz.html        # Privacy policy (German)
├── datenschutz-en.html     # Privacy policy (English)
├── impressum.html          # Imprint (German)
├── impressum-en.html       # Imprint (English)
├── robots.txt              # Search engine directives
├── sitemap.xml             # Site structure for SEO
├── DEPLOYMENT.md           # Deployment instructions
├── README.md               # This file
└── assets/
    └── img/
        ├── app-icon.png        # App icon
        ├── Main_page.jpg       # App screenshot
        ├── Status_page.jpg     # Analytics screenshot
        ├── Settings_page.jpg   # Settings screenshot
        └── favicon_io/         # Favicon files
```

## 🎯 Page Sections

### Hero Section
- Compelling headline with gradient text effects
- App description and value proposition
- **Temporary**: Download unavailable banner (easily removable)
- Primary CTA button (currently disabled)

### Features Section
- Six key app features with icons and descriptions
- Hover effects and smooth animations
- Responsive grid layout

### Screenshots Gallery
- Three app screenshots with captions
- Mobile-optimized presentation
- Lazy loading for performance

### Download Section
- **Temporary**: Download not ready notice
- Disabled download buttons with visual feedback
- iOS coming soon information
- App compatibility details

### Footer
- Quick navigation links
- Legal pages (privacy, imprint)
- Contact information
- Multi-language support

## 🌍 Internationalization

### Supported Languages
- **German (DE)**: Default language
- **English (EN)**: Full translation available

### Translation System
- Dynamic language switching
- LocalStorage persistence
- URL parameter support (`?lang=en`)
- Automatic meta tag updates
- Language-specific legal page routing

### Adding New Languages
1. Extend the `translations` object in `index.html`
2. Add corresponding legal pages (`datenschutz-[lang].html`)
3. Update language switcher options

## 📦 Deployment

### Netlify (Current)
- **Live URL**: https://tracker-app-webpage.netlify.app/
- Automatic deployments from GitHub
- Custom domain ready
- Performance optimizations enabled

### Alternative Platforms
```bash
# Vercel
vercel --prod

# GitHub Pages
# Push to gh-pages branch

# Firebase Hosting
firebase deploy
```

## � Temporary Features (Remove When App Goes Live)

### Download Banner Removal
1. **CSS**: Remove styles with `/* TEMPORARY */` comments
2. **HTML**: Remove `download-not-available` div elements
3. **JavaScript**: Remove `temp.*` translation keys
4. **Classes**: Remove `download-disabled` from buttons

### Enable Download Buttons
1. Remove `download-disabled` class
2. Add actual Google Play Store URL
3. Update `aria-label` attributes
4. Test download functionality

## 🚀 Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## � Related

- [Main App Repository](../tracker-app/) - The actual Android application
- [Privacy Policy](./datenschutz.html) - German privacy policy
- [Privacy Policy EN](./datenschutz-en.html) - English privacy policy

## 📞 Contact

- **Email**: mail@sebastian-rothe.com
- **GitHub**: https://github.com/Sebastian-Rothe/tracker-app
- **Website**: https://tracker-app-webpage.netlify.app/

---

**Made with ❤️ for building better habits**