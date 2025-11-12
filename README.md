# workout-tracker
my workout plan and tracker app

# 💪 24-Week Muscle Builder - Workout Tracker

A comprehensive, browser-based workout tracking application for a complete 24-week progressive muscle building program. Track every set, rep, and RPE across three distinct training phases designed to build 15-20 lbs of muscle.

## 🎯 Live Demo

Access the app: `https://LukeTLukose.github.io/workout-tracker`

## 📱 Features

- **Complete 24-Week Program** - Three progressive training phases
- **80+ Exercises** - Comprehensive exercise database with progression guidance
- **Set Tracking** - Log weight, reps, and RPE for every set
- **Rest Timer** - Built-in countdown timer between sets
- **Progress Dashboard** - Track total workouts, consistency rate, and phase progress
- **Data Export** - Export workout history as JSON or CSV
- **Mobile Optimized** - Responsive design for phone and tablet use
- **Offline Capable** - Works without internet connection once loaded
- **Local Storage** - All data saved locally in your browser

## 🏋️‍♂️ Program Structure

### Phase 1: Foundation Building (Weeks 1-4)
Build foundational strength and movement patterns with moderate weights and focus on form.

**Training Split:**
- Upper Body Strength
- Lower Body Foundation  
- Full Body Integration
- Upper/Lower Circuit
- Active Recovery Days

### Phase 2: Progressive Loading (Weeks 5-12)
Increase training intensity and volume with power development focus.

**Training Split:**
- Push Focus
- Pull Focus
- Legs Focus
- Upper Body Power
- Lower Body Power
- Active Recovery Days

### Phase 3: Specialized Push/Pull/Legs (Weeks 13-24)
Advanced training split with high volume and specialized muscle group focus.

**Training Split:**
- Push A (Chest Focus)
- Pull A (Back Width)
- Legs A (Quad/Glute)
- Push B (Shoulder Focus)
- Pull B (Back Thickness)
- Active Recovery Days

## 📈 Progressive Overload Strategy

**Double Progression Method:**
1. Start at bottom of rep range with manageable weight
2. Increase reps each workout until reaching top of range
3. Once all sets hit top range, increase weight by 2.5-5 lbs
4. Return to bottom of rep range and repeat

**RPE Tracking:**
Rate of Perceived Exertion (6-10 scale) helps manage training intensity and prevent overtraining.

## 🚀 How to Use

### Installation
1. **Clone or Download** this repository
2. **Open `index.html`** in any modern web browser
3. **Bookmark the page** for easy access
4. **On Mobile:** Add to home screen for app-like experience

### Daily Workflow
1. Select your current week and day
2. Follow the warmup protocol
3. Complete each exercise, logging weight/reps/RPE
4. Use rest timer between sets
5. Complete cooldown
6. Finish workout to save progress

### Data Management
- **Backup Regularly:** Use "Export All Data (JSON)" in Settings
- **View Progress:** Check Progress tab for workout history and consistency
- **Export Reports:** Generate CSV files for detailed analysis
- **Reset Data:** Clear all data option available in Settings

## 🛠️ Technology Stack

- **HTML5** - Structure and semantic markup
- **CSS3** - Responsive design with CSS Grid and Flexbox
- **Vanilla JavaScript** - No frameworks or dependencies
- **LocalStorage API** - Client-side data persistence
- **PWA Ready** - Progressive Web App capabilities

## 📊 Data Structure

All workout data is stored locally in browser localStorage:
```javascript
{
  currentWeek: 1,
  currentDay: 1,
  currentPhase: 1,
  workoutHistory: [...],
  completedSets: {
    "week-day-exerciseId": [{weight, reps, rpe, timestamp}]
  }
}
```

## 🔒 Privacy & Security

- **100% Local** - All data stored in your browser
- **No Server** - No data sent to external servers
- **No Tracking** - No analytics or user tracking
- **Offline First** - Works completely offline after initial load

## 📱 Mobile Installation

### iOS (iPhone/iPad):
1. Open in Safari browser
2. Tap Share button
3. Select "Add to Home Screen"
4. Name it "Muscle Builder"
5. Access from home screen like native app

### Android:
1. Open in Chrome browser
2. Tap menu (three dots)
3. Select "Add to Home Screen"
4. Name it "Muscle Builder"
5. Access from home screen like native app

## 🎓 Usage Tips

- **Consistency is Key** - Follow the 5-day training schedule
- **Form Over Weight** - Master technique before adding weight
- **Track Everything** - Log every set for accurate progression tracking
- **Use RPE Honestly** - This prevents overtraining and injury
- **Follow Rest Days** - Recovery is essential for muscle growth
- **Export Data Weekly** - Regular backups prevent data loss

## 🔄 Updates & Versioning

**Current Version:** Final Production (November 2024)

To update your app:
1. Download latest `index.html`
2. Replace old file
3. Hard refresh browser (Ctrl+Shift+R)
4. Your data persists automatically

## 📝 Future Enhancements

Potential features for future versions:
- [ ] 1RM calculator
- [ ] Body measurement tracking
- [ ] Progress photos with comparison
- [ ] Nutrition tracking integration
- [ ] Exercise video library
- [ ] Cloud sync option
- [ ] Social sharing features
- [ ] Advanced progression analytics

## 🤝 Contributing

This is a personal workout tracker. Feel free to fork and customize for your own training needs.

## 📄 License

This project is open source and available for personal use.

## ⚠️ Disclaimer

This workout program is for informational purposes only. Consult with a healthcare provider or certified fitness professional before starting any new exercise program. The author is not responsible for any injuries or health issues that may result from following this program.

## 💡 Support

For questions or issues:
- Check browser console for error messages
- Ensure JavaScript is enabled
- Clear browser cache if experiencing issues
- Export data before troubleshooting

---

**Built with 💪 for serious lifters ready to transform their physique over 24 weeks of progressive training.**

Start Date: ___________  
Goal: Build 15-20 lbs of muscle  
Current Week: 1  
Let's get strong! 🚀
