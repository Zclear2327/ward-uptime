# ward-uptime

Asks GitHub to check the agent server's two addresses every 15 minutes (`.github/workflows/uptime.yml`).

**Measured 2026-11-19: GitHub ran it only 9 times in 2.8 days (every 4 to 9 hours), not every 15 minutes.** GitHub treats
schedules as best effort, so this is a slow backstop, not a 15-minute monitor. A failed run emails the
repository owner. Run it by hand from the Actions tab with **Run workflow**.
