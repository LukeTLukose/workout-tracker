# workout-tracker
my workout plan and tracker app

# 💪 24-Week Muscle Builder - Workout Tracker

A comprehensive, browser-based workout tracking application for a complete 24-week progressive muscle building program. Track every set, rep, and RPE across three distinct training phases designed to build 15-20 lbs of muscle.

## 🎯 Live Demo

Access the app: `https://LukeTLukose.github.io/workout-tracker`

## 📱 Features

### Core Functionality
- **Complete 24-Week Program** - Three progressive training phases
- **80+ Exercises** - Comprehensive exercise database with progression guidance
- **Set Tracking** - Log weight, reps, and RPE for every set
- **Edit & Delete Sets** - Modify completed sets inline, fix typos or errors
- **Rest Timer** - Built-in countdown timer between sets
- **Progress Dashboard** - Track total workouts, consistency rate, and phase progress
- **Mobile Optimized** - Responsive design for phone and tablet use
- **Offline Capable** - Works without internet connection once loaded
- **Local Storage** - All data saved locally in your browser

### Smart Training Features
- **Previous Max Display** - View your last workout performance for each exercise
- **Dynamic Weight Suggestion** - Auto-suggests weight based on double progression logic
- **Demo Video Links** - One-click access to YouTube form demonstrations for every exercise
- **Ab Exercise Integration** - Daily ab work in weeks 6-24 for core development

### Data Management
- **Import/Export Data** - Transfer workout history via JSON or CSV formats
- **CSV Export** - Generate spreadsheet-friendly reports for analysis
- **JSON Backup** - Complete data backup for migration or recovery
- **Data Portability** - Move workout data between devices seamlessly

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
Increase training intensity and volume with power development focus. **Ab exercises added to every workout.**

**Training Split:**
- Push Focus + Abs
- Pull Focus + Abs
- Legs Focus + Abs
- Upper Body Power + Abs
- Lower Body Power + Abs
- Active Recovery (Ab-focused workout)

### Phase 3: Specialized Push/Pull/Legs (Weeks 13-24)
Advanced training split with high volume and specialized muscle group focus. **2 ab exercises per workout day.**

**Training Split:**
- Push A (Chest Focus) + Abs
- Pull A (Back Width) + Abs
- Legs A (Quad/Glute) + Abs
- Push B (Shoulder Focus) + Abs
- Pull B (Back Thickness) + Abs
- Active Recovery (Ab-focused workout)

## 📈 Progressive Overload Strategy

**Double Progression Method:**
1. Start at bottom of rep range with manageable weight
2. Increase reps each workout until reaching top of range
3. Once all sets hit top range, increase weight by 2.5-5 lbs
4. Return to bottom of rep range and repeat

**Smart Weight Suggestions:**
- App automatically suggests weight based on your last workout
- Main lifts (bench, squat, deadlift, overhead press): +5 lbs progression
- Accessory exercises: +2.5 lbs progression
- Displays final set from previous workout for reference

**RPE Tracking:**
Rate of Perceived Exertion (6-10 scale) helps manage training intensity and prevent overtraining.

## 🚀 How to Use

### Installation
1. **Clone or Download** this repository
2. **Ensure both files are present:**
   - `index.html` (main app)
   - `demo-links.json` (exercise video URLs)
3. **Open `index.html`** in any modern web browser
4. **Bookmark the page** for easy access
5. **On Mobile:** Add to home screen for app-like experience

### Daily Workflow
1. Select your current week and day
2. Follow the warmup protocol
3. Review suggested weight (based on previous workout)
4. Watch demo video if needed (click ▶️ icon)
5. Complete each exercise, logging weight/reps/RPE
6. Edit sets if you make a mistake
7. Use rest timer between sets
8. Complete cooldown
9. Finish workout to save progress

### Data Management
- **Backup Regularly:** Use "Export All Data (JSON)" in Settings
- **Import Data:** Transfer workout history from another device
- **View Progress:** Check Progress tab for workout history and consistency
- **Export Reports:** Generate CSV files for detailed analysis in Excel/Sheets
- **Edit History:** Click edit icon on completed sets to modify data
- **Reset Data:** Clear all data option available in Settings

### Customizing Demo Videos
1. Open `demo-links.json` in GitHub or text editor
2. Find exercise ID (e.g., `"barbell-bench-press"`)
3. Replace YouTube URL with your preferred video
4. Save file - changes apply on next page load

## 🛠️ Technology Stack

- **HTML5** - Structure and semantic markup
- **CSS3** - Responsive design with CSS Grid and Flexbox
- **Vanilla JavaScript** - No frameworks or dependencies
- **LocalStorage API** - Client-side data persistence
- **Fetch API** - JSON file loading for demo videos
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

**Files:**
- `index.html` - Main application (all tracking functionality)
- `demo-links.json` - Exercise video URL mappings (77 exercises)

## 🎥 Demo Videos

All exercises include YouTube Short demonstrations:
- **Quick Reference** - Under 1 minute per video
- **Proper Form** - Focus on technique and safety
- **Mobile Friendly** - Opens in YouTube app on mobile devices
- **Easy Editing** - Update URLs in `demo-links.json` file

Featured instructors: Davis Diley (@DavisDiley), Andrew Kwong (@DeltaBolic), and other reputable fitness professionals.

## 🔒 Privacy & Security

- **100% Local** - All data stored in your browser
- **No Server** - No data sent to external servers
- **No Tracking** - No analytics or user tracking
- **Offline First** - Works completely offline after initial load
- **Your Data, Your Control** - Export anytime, delete anytime

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
- **Form Over Weight** - Master technique before adding weight (watch demo videos!)
- **Track Everything** - Log every set for accurate progression tracking
- **Use RPE Honestly** - This prevents overtraining and injury
- **Follow Rest Days** - Recovery is essential for muscle growth
- **Export Data Weekly** - Regular backups prevent data loss
- **Review Previous Max** - Check what you did last time before starting
- **Trust the Suggestions** - Weight recommendations use proven double progression
- **Edit Mistakes Immediately** - Don't let typos corrupt your progression data

## 🔄 Updates & Versioning

**Current Version:** Enhanced Production (December 2024)

**Recent Updates:**
- ✅ Edit & delete completed sets
- ✅ Import/Export data (CSV & JSON)
- ✅ Ab exercises integrated (weeks 6-24)
- ✅ Previous max display with smart weight suggestions
- ✅ Demo video links for all exercises

To update your app:
1. Download latest files (`index.html` + `demo-links.json`)
2. Replace old files
3. Hard refresh browser (Ctrl+Shift+R)
4. Your data persists automatically

## 📝 Future Enhancements

Potential features for future versions:
- [ ] 1RM calculator
- [ ] Body measurement tracking
- [ ] Progress photos with comparison
- [ ] Nutrition tracking integration
- [ ] Cloud sync option
- [ ] Social sharing features
- [ ] Advanced progression analytics
- [ ] Custom workout builder

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
- Verify both `index.html` and `demo-links.json` are in same directory
- Clear browser cache if experiencing issues
- Export data before troubleshooting

---

**Built with 💪 for serious lifters ready to transform their physique over 24 weeks of progressive training.**

Start Date: ___________  
Goal: Build 15-20 lbs of muscle  
Current Week: 1  
Let's get strong! 🚀
