# Daniel's Frontier 0.8.1.2 Hotfix

- Adds Esc > Connection diagnostics: request/server timings, download and snapshot costs, frame stalls, snapshot age and HTTP failures.
- Send report to support delivers the recent timing capture directly to the private server inbox and confirms a receipt. No file handling is required. Includes your pilot name for support; excludes passwords and chat.
- Copy/save report remain available. Uploads happen only when selected; latest submission replaces the player's previous report, with bounded retention and rate limits.
- Matching server captures its own timing data alongside the submitted client report for correlation. No public report-reading endpoint is exposed.
- Preserves Design A engines, gameplay, movement speed and balance. The updater binary is unchanged.
