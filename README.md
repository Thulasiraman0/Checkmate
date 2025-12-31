# ♚ Checkmate - Daily Habit Tracker

**Keep your streaks alive!**

A modern, interactive habit tracking application designed to help you build and maintain positive daily habits. Track up to 31 days of habits with visual feedback, daily reminders, and a sleek dark-themed interface.

## 🎯 Features

✨ **Core Features:**
- 📊 **31-Day Tracker**: Track habits for the entire month with an intuitive grid
- 🎨 **Beautiful UI**: Dark theme with animated bubble backgrounds and modern fonts
- 📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- 🔔 **Daily Notifications**: Get reminded at a specific time each day to complete your habits
- 💾 **Local Storage**: All data is saved locally in your browser (no server needed)
- 🗓️ **Month/Year Selection**: Track habits for different months and years
- ♚ **Chess-Themed Design**: Elegant checkmate-inspired header with letter tiles

✅ **Habit Tracking:**
- **Three Status States**:
  - ✓ Mission Successful (Green)
  - ✕ Incomplete (Red)
  - \- Moderate (Yellow)
- Click any day to cycle through status states
- Add unlimited custom habits
- Delete habits you no longer need
- Edit habit names anytime

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - it's a single HTML file!

### Option 1: Local Use
1. Download `Checkmate.html` from the repository
2. Double-click the file to open it in your browser
3. Start tracking your habits!

### Option 2: Netlify Deployment (Recommended)

**Step 1: Fork/Clone the Repository**
```bash
git clone https://github.com/Thulasiraman0/Checkmate.git
cd Checkmate
```

**Step 2: Deploy to Netlify**
1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub (or email)
3. Click "New site from Git"
4. Select "GitHub" and authorize
5. Choose the "Checkmate" repository
6. Click "Deploy"
7. Your site will be live in seconds!

**Live URL Example:**
```
https://checkmate-habit-tracker.netlify.app
```

## 📖 How to Use

### Basic Tracking
1. **Add a Habit**: Click the "+ Add Habit" button
2. **Name Your Habit**: Type the habit name (e.g., "Exercise", "Meditation")
3. **Track Daily**: Click any day cell to cycle through:
   - Empty (blank)
   - ✓ Success (Green)
   - ✕ Incomplete (Red)
   - \- Moderate (Yellow)
4. **View Progress**: Watch your streaks build across the month

### Monthly View
- Use the **Month** dropdown to select any month
- Use the **Year** input to navigate to different years
- Your data persists for each month/year combination

### Daily Reminders
1. Check the **"Daily Reminder"** checkbox
2. Set your preferred notification time (default: 7:00 PM)
3. Click **"Test Notification"** to preview
4. When the time arrives, you'll get a browser notification
5. Click the notification to focus on the app

### Data Management
- **Reset**: Click the "↻ Reset" button to clear all checkmarks for the current month
- **Delete Habit**: Hover over a habit name and click the "×" button
- **All data is saved automatically** to your browser's local storage

## 🛠️ Technical Details

### Technology Stack
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations and responsive design
- **Vanilla JavaScript** - No frameworks or dependencies
- **Google Fonts** - Poppins, Space Grotesk, Playfair Display

### Browser Compatibility
| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome | ✅ | ✅ |
| Firefox | ✅ | ✅ |
| Safari | ✅ | ✅ 16.4+ |
| Edge | ✅ | ✅ |

### Data Storage
- Uses **browser's localStorage** API
- Falls back to in-memory storage for private/incognito mode
- Each user gets isolated data
- No data sent to any server

### Notifications
- Uses **Browser Notification API**
- Requires user permission (one-time)
- Works even with browser minimized
- Each browser/device is independent

## 🎨 Customization

### Change Default Time
Edit line in the notification initialization:
```javascript
// Change '19:00' to your preferred time
const settings = { enabled: false, time: '19:00' };
```

### Modify Theme Colors
Edit CSS variables in the style section:
```css
:root {
    --accent-blue: #1d4ed8;
    --accent-red: #dc2626;
    --status-success: #22c55e;
    /* ... more colors ... */
}
```

## 📱 Mobile Tips

✅ **Best Practices:**
- Add to home screen (iOS/Android) for quick access
- Use full-screen mode for immersive experience
- Landscape mode shows more days at once
- Swipe left/right to see all 31 days

## ⚠️ Important Notes

### Data Privacy
- ✅ All data stays on your device
- ✅ No tracking or analytics
- ✅ No account creation required
- ✅ No data sent to any server

### Limitations
- Data is device-specific (use different devices = different data)
- Clearing browser cache will erase data
- Notifications require browser to be running
- Some corporate firewalls may block notifications

## 🤝 Contributing

Found a bug? Want to suggest a feature?
1. Open an issue on GitHub
2. Include screenshots if possible
3. Describe the problem clearly

## 📝 License

This project is open source and available to everyone.

**Created by:** Thulasiraman
**Last Updated:** December 31, 2025

---

## 🎯 Quick Start Summary

```
1. Download Checkmate.html
2. Open in browser
3. Add your habits
4. Click days to track
5. Enable notifications for reminders
6. Deploy to Netlify to share with others
```

## 💡 Pro Tips

1. **Habit Stacking**: Group related habits together
2. **Realistic Goals**: Start with 3-5 habits, build from there
3. **Daily Ritual**: Check the app at the same time each day
4. **Week View**: Look at weekly patterns to identify trends
5. **Monthly Review**: Review month-end to celebrate progress

## 🔗 Links

- 📦 GitHub Repository: [Checkmate](https://github.com/Thulasiraman0/Checkmate)
- 🚀 Deploy on Netlify: [netlify.com](https://netlify.com)
- 📖 Browser Notification API: [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/API/Notification)

---

**Remember:** Building habits is a marathon, not a sprint. Keep your streaks alive! 🎯✨

For questions or support, please open an issue on GitHub.
