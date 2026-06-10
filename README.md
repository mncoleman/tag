# Orb Tag — mncoleman

A single-file, top-down multiplayer game of tag through an obstacle arena. Pick an emoji orb, dodge through the course, and tag others to score.

**Play:** [tag.mncoleman.com](https://tag.mncoleman.com)

## Features
- Top-down obstacle arena with camera follow + minimap
- Emoji orb avatars (pick in the lobby, change live with **E**)
- Four tag rule sets: classic (tagged becomes IT), timer rotation, race to 10 tags, and one permanent tagger
- Tagged orbs vanish and respawn at a random spot
- Activity feed (who tagged who, who's IT) + banners
- AI bots fill the arena (toggle with **B**)
- Multiplayer:
  - **Local auto-join** — open in multiple tabs/windows on one machine (BroadcastChannel)
  - **Online room** — share a 6-char room code to play across devices (PeerJS relay)
- Mobile optimized (portrait + landscape) with an on-screen joystick
- Refresh/close protection during a match

## Tech
Everything is in `index.html` — no build step, no dependencies except PeerJS (loaded from CDN only for Online rooms). Hosted on GitHub Pages.

## Controls
- **Move:** WASD / Arrows, or drag on touch
- **E:** change your orb emoji
- **B:** toggle bots

---
Built with [Claude Code](https://claude.com/claude-code).
