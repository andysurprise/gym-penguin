# Gym Penguin - Workout Tracker

## Features
- Glacier blue themed design optimized for iPhone 16
- Sporty penguin mascot with headband
- Tracks chin-ups, push-ups, and plank exercises
- Records sets and automatically times 90-second rest periods
- Persistent storage that works with Apple Private Relay
- Large, legible typography with minimal dark design

## Deploying to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to https://github.com and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., "gym-penguin")
4. Make it **Public**
5. Click "Create repository"

### Step 2: Upload Your Files
1. On your new repository page, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Scroll down and click "Commit changes"

### Step 3: Enable GitHub Pages
1. In your repository, click "Settings" (top menu)
2. In the left sidebar, click "Pages"
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/ (root)"
5. Click "Save"

### Step 4: Access Your App
After a few minutes, your app will be live at:
```
https://[your-username].github.io/[repository-name]/
```

For example: `https://johnsmith.github.io/gym-penguin/`

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

## Adding to iPhone Home Screen
1. Open the app in Safari
2. Tap the Share button
3. Scroll and tap "Add to Home Screen"
4. Name it "Gym Penguin" and tap "Add"

The app will now launch like a native app with no browser chrome, perfect for quick access at the gym!
