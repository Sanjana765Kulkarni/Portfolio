# 🎨 Sanjana Kulkarni's Portfolio

A modern, AI-powered portfolio website built with vanilla HTML, CSS, and JavaScript. Features a Notion-inspired design with real-time GitHub integration and intelligent project recommendations.

## ✨ Features

- 🎨 **Notion-Style Design** - Clean, professional aesthetic with light/dark themes
- 🤖 **AI-Powered Recommendations** - Smart project suggestions based on visitor behavior
- 📊 **Live GitHub Integration** - Real-time repository fetching and contribution graph
- 💯 **LeetCode Stats** - Automatic problem-solving statistics
- 📱 **Fully Responsive** - Optimized for mobile and desktop
- ⚡ **Zero Dependencies** - Pure vanilla JavaScript, no frameworks needed
- 🚀 **Single File Deployment** - Everything in one HTML file

## 🚀 Quick Start

### View Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sanjana765Kulkarni/Portfolio.git
   cd Portfolio
   ```

2. **Open in browser:**
   - Simply double-click `portfolio.html`
   - OR use a local server:
     ```bash
     python -m http.server 8000
     # Visit: http://localhost:8000/portfolio.html
     ```

### Deploy Online

**GitHub Pages (Recommended):**
1. Rename `portfolio.html` to `index.html`
2. Push to GitHub
3. Enable GitHub Pages in Settings → Pages
4. Your site will be live at `https://Sanjana765Kulkarni.github.io/Portfolio/`

See [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md) for detailed deployment options.

## 📁 Project Structure

```
Portfolio/
├── portfolio.html          # Main portfolio (complete website)
├── styles.css             # Separate CSS (optional)
├── DEPLOYMENT_GUIDE.md    # Detailed deployment instructions
├── QUICK_START.md         # Fast deployment guide
├── FINAL_CHECKLIST.md     # Verification checklist
├── GITHUB_CHART_INFO.md   # GitHub chart documentation
├── START_HERE.md          # Quick overview
└── README.md              # This file
```

## 🎯 Key Sections

- **Home/Profile** - Introduction and contact information
- **Stats** - LeetCode statistics and GitHub contribution graph
- **Skills** - Organized by category (AI/ML, Cloud, Tools, etc.)
- **Projects** - Auto-fetched from GitHub repositories
- **Gallery** - Project screenshots and demos
- **Blogs** - Links to blog posts and articles

## 🤖 AI Recommendation System

The portfolio includes a client-side AI engine that:
- Tracks visitor behavior (scroll, clicks, time spent)
- Analyzes interests based on interactions
- Recommends relevant projects
- Updates in real-time (every 15 seconds)
- **Privacy-first:** All data stays in the browser, nothing sent to servers

## 🛠️ Customization

### Update Personal Information

Edit `portfolio.html` and search for:
- **Name:** Line ~915
- **Contact:** Lines ~920-933
- **GitHub Username:** Lines ~880, 928, 1511, 1557
- **LeetCode Username:** Lines ~884, 932, 1496

### Change Theme Colors

Edit CSS variables in `portfolio.html` (lines ~11-40):
```css
:root {
    --accent-color: #2383e2;  /* Main accent color */
    --bg-primary: #ffffff;     /* Background color */
}
```

### Add Gallery Images

Replace placeholder divs in the Gallery section with:
```html
<div class="gallery-item">
    <img src="your-image.jpg" alt="Description">
</div>
```

## 📊 Live Data Sources

- **GitHub Repositories:** GitHub REST API
- **GitHub Contributions:** ghchart.rshah.org (with fallbacks)
- **LeetCode Stats:** leetcode-stats-api.herokuapp.com

## 🌐 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ❌ Internet Explorer (not supported)

## 📝 License

This project is open source and available for personal use.

## 👤 Contact

**Sanjana Kulkarni**
- Email: sanjukul7653@gmail.com
- GitHub: [@Sanjana765Kulkarni](https://github.com/Sanjana765Kulkarni)
- LeetCode: [@KulkSanjana](https://leetcode.com/KulkSanjana)

## 🙏 Acknowledgments

- Design inspiration: [Notion.so](https://notion.so)
- Icons: [Lucide Icons](https://lucide.dev)
- Font: [Inter](https://rsms.me/inter/) by Rasmus Andersson

---

**Built with ❤️ using vanilla HTML, CSS, and JavaScript**
