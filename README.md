# BEAMdisplay

Shows why external displays don't all light up on an Apple silicon Mac, and fixes what it can. BEAMdisplay lists the Mac's GPU display engines and which are in use, what's plugged into each Thunderbolt/HDMI port, and every display macOS knows about, then explains the problem in plain language. **Force Connect All** re-scans the ports, turns on disabled displays and splits mirrors; **One Engine Each** lowers any display running above 4K60 so it uses one display engine instead of two. By [BEAM Events](https://beamevents.com).

This repository only holds the **installers and updates**.

## Download
Get the latest version from **[Releases](https://github.com/BEAMevents/BEAMdisplay/releases/latest)**:

- **Mac (Apple Silicon): BEAMdisplay-x.y.z.dmg**: open it and drag BEAMdisplay to Applications. It updates itself from then on.

The app isn't notarized yet. The first time, open it, click **Done**, then go to System Settings → Privacy & Security and click **Open Anyway**.

## Updates
BEAMdisplay checks for updates in the background and shows **Update x.y.z ready** in its header. Click it (or the version number), then **Install & Restart**. You can also use **BEAMdisplay → Check for Updates…**.
