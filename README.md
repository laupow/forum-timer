# Forum Timer

Countdown timer for a 25-minute, two-candidate forum. Single `index.html`, no build step.

Live: https://laupow.github.io/forum-timer/

Changes go through pull requests. Each pull request gets a preview link; merging to `main` updates the live site.

- 15 segments: introduction, opening statements, three questions with answers, closing statements
- Scroll down (or press C) for moderator controls
- 30-minute session clock in the controls, independent of segment timers; starts with the first segment
- Screen turns yellow at 20 seconds left and red at 5; bell at time up
- After time up the screen flashes red for 3 seconds, then the next segment starts (A toggles auto-advance)
- Warnings are visual only; the bell rings once at time up. M mutes, B rings the bell
- Keys: Space start/pause, ← → previous/next, R restart, + − 15 seconds, A auto-advance, F fullscreen, Home reset
- `?speed=20` runs the clock 20× faster for testing
