# GrowthQuest React

## What works now
- Login and sign up with persistent local session
- Onboarding save/load
- Protected routes
- Habit logging with saved XP, streaks, total days, weekly and monthly charts
- Dynamic badge unlocks
- Profile name save
- Theme persistence
- Data export
- Logout

## Run
```bash
npm install
npm run dev
```

## Notes
This version uses a browser-backed local data layer so the full app flow works immediately without external setup. The backend adapter lives in `src/lib/backend.js`.
