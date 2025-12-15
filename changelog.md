# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.1.0] - 2024-12-16

### Added
- 📊 Comprehensive workout history dashboard with interactive charts
- 📈 Progress line chart showing rep count over last 10 workouts
- 🍩 Exercise distribution doughnut chart
- 🏆 Statistics panel showing total workouts, reps, favorite exercise, and average form score
- 🔥 Best workout streak tracker
- ⏱️ Total time spent working out calculator
- 💾 CSV export functionality for workout data
- 🗑️ Delete individual workout sessions
- 🗑️ Clear all history feature
- 🎨 Smooth animations for history modal
- ⏳ Loading state for history data fetch
- 💽 Persistent storage using Browser Storage API
- 📊 Chart.js integration for data visualization

### Changed
- 🎨 Enhanced UI with glassmorphism effects on history dashboard
- 💪 Improved workout summary to include session statistics

### Fixed
- 🐛 Better error handling for storage operations
- 🔧 Improved data persistence across sessions

---

## [1.0.0] - 2024-12-15

### Added
- 🎯 Real-time pose detection using MediaPipe Pose
- 💪 Support for 5 exercise types:
  - Bicep Curls
  - Push-ups
  - Pull-ups
  - Sit-ups
  - Squats
- 📊 Real-time form evaluation and feedback
- 🔄 Automatic rep counter
- 🕒 Session timer
- 🌗 Dark and Light mode toggle with persistence
- 🎨 Modern gradient UI with animations
- ⭐ Animated background with stars
- 📐 Joint angle calculation and visualization
- 🎯 Progress circle showing current angle
- 💯 Form score tracking
- 📊 Stats dashboard (total reps, current exercise, form score)
- 🎮 Exercise selection buttons
- 🔄 Reset counter functionality
- ⏹️ Stop workout feature
- 📱 Responsive design for various screen sizes
- 🎨 Glassmorphism and modern CSS effects
- ⚡ Smooth transitions and hover effects

### Technical Details
- HTML5 Canvas for pose visualization
- MediaPipe Pose for skeletal tracking
- Custom JavaScript for exercise logic
- CSS3 animations and gradients
- Webcam integration for real-time tracking

---

## [Unreleased]

### Planned Features
- 🔊 Voice announcements for rep counts
- 🎯 Goal setting and achievement system
- 📱 Enhanced mobile responsiveness
- 🌐 Multi-language support
- 🔔 Workout reminders
- ☁️ Cloud sync option
- 🤖 AI-powered workout recommendations
- 📅 Custom workout plans
- 👥 Social sharing features

---

## Version Format

**[MAJOR.MINOR.PATCH]**
- **MAJOR**: Breaking changes or major feature releases
- **MINOR**: New features (backward compatible)
- **PATCH**: Bug fixes and small improvements

---

## Categories

- **Added**: New features
- **Changed**: Changes to existing functionality
- **Deprecated**: Features that will be removed
- **Removed**: Removed features
- **Fixed**: Bug fixes
- **Security**: Security improvements