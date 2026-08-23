# Party Word Guess Runtime

Standalone playable runtime derived from the canonical Lovable design source. This runtime is intentionally self-contained so it can run as a Render static site without Lovable.

## Real gameplay included
- Gyroscope / DeviceOrientation with iOS permission request
- Correct: beta > +40°
- Pass: beta < -40°
- Neutral dead zone: -25°..+25°
- 1.2s debounce
- 30 / 60 / 90 second rounds
- Fisher-Yates shuffle
- Countdown, correct, pass, time-up, pause and result states
- Manual fallback buttons
- Screen Wake Lock when supported
- Web Audio feedback
- Haptics when supported
- Web Share with clipboard fallback
- PWA manifest + service worker

The visual system follows the real Lovable source design tokens and component direction preserved in `design-master/`.
