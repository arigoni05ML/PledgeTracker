# PledgeTracker
Pledge Tracker for VC. A small installable web app for sending the morning pledge and the end-of-day (EOD) results to WhatsApp.

## Features
- **Pledge and EOD messages** built from what you type, then copied or sent straight to WhatsApp.
- **Daily reset**: the leader, pledges and EOD actuals clear themselves at midnight.
- **Reminders** based on the store's opening hours (editable in Settings):
  - An in-app banner when the pledge or EOD is due and hasn't been sent.
  - Notifications while the app is running in the background.
  - **Add reminders to Calendar**: weekly calendar alerts that work even when the app is closed.
- **Settings** (⚙️ in the header): light, dark or system theme, store name, opening hours, reminder timing, editable message templates, and pledge/EOD lines you can add, edit, hide and reorder.

Default hours: Mon–Tue 9:00–18:00, Wed 9:00–19:00, Thu–Fri 9:00–21:00, Sat 9:00–18:00, Sun 13:00–18:00.

When you change any file, bump `VERSION` in `sw.js` so installed copies update.
