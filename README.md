# launch91-reply-check

Runs the Launch91 email reply check every 30 minutes on GitHub Actions (free for public repos).
The code is checked out from a private repo at run time; this repo holds only the schedule.
Logs show only "ok" or "FAILED", never contact details. Secrets are stored as encrypted Actions secrets.
