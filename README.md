# RunCast 🎵

**Run to the beat.** RunCast generates a Spotify playlist matched to your running cadence — segment by segment, mood by mood.

## How it works

1. Connect your Spotify account
2. Enter your height (used to calculate stride length → cadence → BPM)
3. Build your workout: one row per km, set your pace and energy mood
4. RunCast calls the Spotify API and returns real songs matched to each segment's BPM and energy
5. Save the playlist directly to your Spotify account

## Energy moods

| Mood | Use it for |
|------|-----------|
| Warmup | First km, easing in |
| Steady | Comfortable cruise pace |
| Push | Picking up the pace |
| Peak 🔥 | That km where you need a lift |
| Cooldown | Last stretch, winding down |

## Tech

- Pure vanilla JS — no framework, no build step
- Spotify Web API (implicit grant OAuth flow)
- PWA — installable on Android/iOS from the browser
- Hosted on GitHub Pages

## Setup

No setup needed — just visit the live URL.

To run locally, serve with any static server:
```
npx serve .
```

## Roadmap

- [ ] Gym mode (HIIT, strength sessions)
- [ ] Half-time BPM detection
- [ ] Play preview in-app
- [ ] Android APK / Play Store release
