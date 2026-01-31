# SEB – Modified Build
README Created by ChatGPT
This is a modified Windows build of Safe Exam Browser (SEB).

## What’s changed

### Clipboard
- Clipboard is no longer cleared
- Copy & paste works

### Window / Focus Restrictions
- No detection of other open windows
- No reaction when another app is on top
- SEB does not care if focus is lost

### Process Handling
- External apps are no longer force‑closed
- Apps like browsers, OBS, Discord, etc. can stay running

### Integrity Checks
- Self‑integrity verification removed
- No tamper detection

### Environment
- SEB still runs in its own environment
- Task Manager can be accessed
- Other apps can be launched from system tools
- Some shortcuts (e.g. Alt+Tab) still don’t work due to how the environment is created

### Screen Capture
- Screen recording is no longer blocked
- Full display capture works with third‑party software
- Built‑in Windows screenshot tools still don’t work

## Platform
- Windows only
- macOS not supported

## Notes
- Behavior depends on SEB version
- Newer versions enforce version checks more aggressively
- GUI was kept unchanged to avoid anything visually obvious

## Status
- Actively tested
- Updates may be irregular

---

Created by **@303entity303**
