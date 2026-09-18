MCA RESULTS DASHBOARD V5 — PERFORMANCE FIX

- Uses a 120-second local snapshot cache.
- Allows the central voting API up to 100 seconds during a genuine cold start.
- Runs one memory-conscious Gunicorn worker with four request threads.
- Retains stale successful data when a later refresh fails.

Deploy after Voting System V23.74.
