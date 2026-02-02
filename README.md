# Gym Penguin - Workout Tracker

## Features
- Glacier blue themed design optimized for iPhone 16
- Sporty penguin mascot with headband
- Tracks chin-ups, push-ups, and plank exercises
- Records sets and automatically times 90-second rest periods
- Persistent storage that works with Apple Private Relay
- Large, legible typography with minimal dark design

## Using the App

### Starting a Workout
1. Tap "START WORKOUT" on the welcome screen
2. You'll see your last workout results for each exercise
3. Adjust target reps/time using the +/- buttons
4. Tap "BEGIN SET" to record the set
5. Rest timer automatically starts (90 seconds)
6. Repeat for all sets and exercises

### Data Persistence
Your workout data is automatically saved after each completed workout and will persist across sessions, even with Apple Private Relay enabled. The app uses Claude's persistent storage API.

### Customization
To modify exercises, rest times, or other settings, edit the `EXERCISES` array in the `index.html` file around line 500.
