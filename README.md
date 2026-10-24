# Forum Timer

Countdown timer for a 23-minute, one-candidate forum. Single `index.html`, no build step.

Live: https://laupow.github.io/forum-timer/

Changes go through pull requests. Each pull request gets a preview link; merging to `main` updates the live site.

- 14 segments: LAC introduction, candidate opening, five questions with answers, candidate closing, LAC closing
- Scroll down (or press C) for moderator controls
- 30-minute session clock in the controls, independent of segment timers; starts with the first segment
- Screen turns yellow at time up (the only color change); bell at time up
- After time up the screen holds yellow for 4 seconds, then the next segment starts (A toggles auto-advance)
- Warnings are visual only; the bell rings once at time up. M mutes, B rings the bell
- Keys: Space start/pause, ← → previous/next, R restart, + − 15 seconds, A auto-advance, F fullscreen, Home reset
- `?speed=20` runs the clock 20× faster for testing
