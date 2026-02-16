# GitHub Contribution Chart - How It Works

## ✅ What's Implemented

Your portfolio now has a **real-time GitHub contribution graph** that automatically updates with your actual GitHub activity.

## 🔄 How It Updates

The contribution chart is fetched **every time** someone visits your portfolio:

1. **On page load** - Automatically fetches your latest contributions
2. **On theme toggle** - Refreshes to match light/dark mode
3. **Real-time data** - Always shows your current GitHub activity

## 📊 Data Sources

The implementation uses a **smart fallback system**:

### Primary Source: ghchart.rshah.org
- Shows the classic GitHub contribution calendar (green squares)
- Updates in real-time from your GitHub profile
- Supports light/dark themes

### Fallback: github-readme-stats
- If the primary source fails, automatically switches to this
- Shows GitHub stats (commits, PRs, issues, stars)
- Also updates in real-time

## 🎨 Features

- ✅ **Real-time updates** - Fetches from GitHub every page load
- ✅ **Theme-aware** - Adapts to light/dark mode
- ✅ **Automatic fallback** - If one API fails, uses another
- ✅ **Loading state** - Shows spinner while loading
- ✅ **Error handling** - Gracefully handles API failures

## 🔍 What You'll See

The contribution graph shows:
- Your contribution activity for the past year
- Green squares for days with contributions
- Darker green = more contributions
- Hover to see exact contribution counts (on GitHub's site)

## 🛠️ Technical Details

**Username:** KulkSanjana  
**API Endpoints:**
- Primary: `https://ghchart.rshah.org/{theme}/KulkSanjana`
- Fallback: `https://github-readme-stats.vercel.app/api?username=KulkSanjana`

**Update Frequency:**
- The APIs fetch fresh data from GitHub on every request
- No caching on your portfolio side
- Always shows your latest contributions

## 🐛 Troubleshooting

**Chart not showing?**
1. Check internet connection
2. Open browser console (F12) to see any errors
3. The fallback should load automatically if primary fails

**Shows old data?**
- Hard refresh the page (Ctrl + F5)
- The APIs update within minutes of GitHub activity

**Want to test it?**
1. Make a commit on GitHub
2. Wait 1-2 minutes
3. Refresh your portfolio
4. You should see the updated contribution graph!

## 📝 Code Location

The function is in `portfolio.html` around line 1494:
```javascript
function updateGitHubGraph() {
    // Fetches real-time GitHub contribution data
    // With automatic fallback if primary source fails
}
```

---

**Your GitHub contributions are now live and updating in real-time! 🎉**
