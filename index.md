---
title: Focus — Support
permalink: /
---

[Privacy policy](privacy/) · [Dansk](da/)

# Focus — Support

Focus is a timer that lives in your macOS menu bar. Click the timer icon to start a session; open **Settings…** (⌘, while the dropdown is open) for everything else.

## Install

- **App Store:** [Focus – Menu Bar Timer](https://apps.apple.com/app/id6833000003)
- **Homebrew, from the App Store:** `brew install mas`, then `mas install 6833000003` (updates come from the App Store)
- **Homebrew, direct:** `brew tap kennethegholm/focus`, `brew trust kennethegholm/focus` (Homebrew asks you to trust third-party taps once), then `brew install --cask focus-menu-bar-timer`. Update with `brew upgrade --cask focus-menu-bar-timer`.

Both are the same app; install one of them.

## Do Not Disturb doesn't turn on

Focus switches Do Not Disturb with two Shortcuts, "Focus On" and "Focus Off". Open Settings → Focus → **Add Shortcuts** and click **Add Shortcut** in both windows that open. Keep the names exactly as they are. To use a different Focus (for example Work), edit the "Set Focus" action inside those two Shortcuts.

If you deleted or renamed them, click **Add Shortcuts** again.

## Do Not Disturb stays on after logging out or shutting down

Known limitation: Focus only turns Do Not Disturb off when a session ends or when you quit Focus from its menu. If your Mac logs out or shuts down mid-session, turn it off in Control Center. A "Block time in calendar" event also keeps its planned length in that case; edit or delete it in Calendar.

## The "Until meeting" button doesn't appear

- Settings → Calendar → **Use calendar** must be on, and Focus must have calendar access (System Settings → Privacy & Security → Calendars).
- It only appears when there's a meeting later today and at least 5 minutes of focus time before it (it ends 5 minutes before the meeting).
- All-day events, declined or cancelled events, and events marked "free" don't count as meetings.
- Only calendars ticked under **Meetings from** count (see below).

## Choose which calendars count as meetings

Settings → Calendar → **Meetings from** (needs **Use calendar**). Click the summary (for example "All calendars") and tick the calendars whose events should count — leave out family, birthdays or holidays. "Until meeting" and "Up next" then ignore the rest. While **All calendars** is chosen, calendars you add later count too; once you've picked specific ones, tick new calendars yourself. With nothing ticked, the button and "Up next" stay hidden.

## Show the next meeting in the menu bar

Settings → Calendar → **Show next meeting in menu bar** (needs **Use calendar**). Under **Show**, pick the title only, the title and start time, or the title and the minutes until it starts.

## Colleagues don't see my focus block

Settings → Calendar → **Block time in calendar** must be on, with a shared calendar (for example your work calendar) picked. Work accounts can take a moment to sync. Choose under "When a session ends" whether the event is shortened to the time you focused or removed.

## Contact

[Open an issue on GitHub](https://github.com/KennethEgholm/focus-app/issues) — questions, bugs and ideas are all welcome.
