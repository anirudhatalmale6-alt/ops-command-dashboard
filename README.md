# Ops Command — Collaborative Task Management Dashboard

Interactive demo of a real-time dashboard fed by multiple function checklists.

- **Central dashboard**: function hierarchy with named responsible leads, live status (progress %, outstanding count, last event), a chronological timestamped event log, and an outstanding-tasks panel aggregating unchecked items across all functions.
- **Function checklists**: each person works their assigned function; ticking an item auto-logs a timestamped event under their name; free-text notes post straight to the central log.
- **Real-time**: the demo syncs live across browser tabs via BroadcastChannel. The production build uses a live server (WebSockets) so remote teammates sync in real time.

Open the page, then open a second tab and switch roles to see multi-user sync.
