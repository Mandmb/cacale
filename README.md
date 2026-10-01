# POPO v18 — Dictionary Loading Fix

- Prevents the game from being stuck on "Loading Spanish dictionary…".
- Uses the cached 2,000+ word dictionary immediately when available.
- Network dictionary fetch now has a 5-second timeout.
- Falls back instead of hanging if the dictionary host is unavailable.
- One-time cleanup unregisters the old v17 service worker and clears its caches.
- v18 no longer registers a service worker.
- POPO branding, mobile layout, no-zoom behavior, hint scoring, and 💩 celebration remain.
