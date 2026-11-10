---
title: Focus — Support
permalink: /
---

[Privacy policy](privacy/) · [Dansk](da/)

# Focus — Support

Focus is a timer that lives in your macOS menu bar. Click the timer icon to start a session; open **Settings…** (⌘, while the dropdown is open) for everything else.

## Do Not Disturb doesn't turn on

Focus switches Do Not Disturb with two Shortcuts, "Focus On" and "Focus Off". Open Settings → Focus → **Add Shortcuts** and click **Add Shortcut** in both windows that open. Keep the names exactly as they are. To use a different Focus (for example Work), edit the "Set Focus" action inside those two Shortcuts.

If you deleted or renamed them, click **Add Shortcuts** again.

## Do Not Disturb stays on after logging out or shutting down

Known limitation in 1.0: Focus only turns Do Not Disturb off when a session ends or when you quit Focus from its menu. If your Mac logs out or shuts down mid-session, turn it off in Control Center.

## The "Until meeting" button doesn't appear

- Settings → Calendar → **Use calendar** must be on, and Focus must have calendar access (System Settings → Privacy & Security → Calendars).
- It only appears when there's a meeting later today and at least 5 minutes of focus time before it (it ends 5 minutes before the meeting).
- All-day events, declined or cancelled events, and events marked "free" don't count as meetings.

## Colleagues don't see my focus block

Settings → Calendar → **Block time in calendar** must be on, with a shared calendar (for example your work calendar) picked. Work accounts can take a moment to sync. Choose under "When a session ends" whether the event is shortened to the time you focused or removed.

## Contact

[Open an issue on GitHub](https://github.com/KennethEgholm/focus-app/issues) — questions, bugs and ideas are all welcome.
