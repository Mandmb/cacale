# POPO v19 — Script and Dictionary Fix

- Fixed the JavaScript runtime error caused by referencing the removed `closeModal` element.
- This restores the help, stats, keyboard, dictionary loading, and game initialization.
- Dictionary loads from local cache when available, otherwise fetches the full Spanish list with a 5-second timeout.
- Falls back instead of hanging if the dictionary source is unavailable.
- Removed stale service-worker registration.
- POPO branding, mobile layout, no-zoom, hint scoring, and 💩 celebration remain.
