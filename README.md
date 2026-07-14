# Maureen Teleconference

A prototype for remote collaboration, made up of two tools:

- **The meeting platform** — a browser-based video meeting app for focused, scheduled meetings.
- **The virtual space** — a cozy, top-down virtual office you explore as an avatar (think Gather Town, but built to feel lived-in). Walk in from the street, up through a multi-floor building of desks and meeting rooms, and out onto a rooftop café.

This repository contains the **virtual space** prototype — a single self-contained HTML file (HTML5 Canvas + JavaScript, no build step, no dependencies).

## Try it

Open `index.html` in a modern browser. That's it — nothing to install.

If GitHub Pages is enabled for this repo, it can also be played directly in the browser at the Pages URL.

## What's in it

- **A multi-floor building** — street entrance, lobby with reception, open-plan office floors, and a rooftop café with a city skyline, string lights, and a jukebox.
- **Move around as an avatar** with proximity-based presence — walk up to people, sit at desks, wave, and react.
- **Coworkers** who wander, sit, and chat, with typing indicators before they speak.
- **Direct messages** with per-person avatar profile pictures, read receipts, and file attachments.
- **A shared cupboard** for dropping files, a guestbook, and a grab-a-coffee rooftop counter.
- **Supervisor screen check-ins**, with the option to show or hide that the screen is being viewed.
- **Cozy detail** — steaming coffee, warm light pools, swaying plants, and ambient sound (room tone indoors, a lo-fi track when the jukebox is on).
- **A build/edit mode** for moving furniture, and tools to add or rearrange floors.

## Controls

| Action | Key |
| --- | --- |
| Move | WASD or arrow keys (or click to walk) |
| Interact (sit, coffee, jukebox, etc.) | E |
| Chat | Enter / T |
| Zoom | Ctrl + scroll |

Toolbar buttons (top-right) cover edit mode, floors/teleport, sound, and avatar/settings.

## Tech

- Plain HTML5 Canvas and vanilla JavaScript in one file — no framework, no build tooling.
- Runs entirely client-side; progress (avatar, furniture, floors) is saved in the browser via `localStorage`.

## Status

A working prototype. Real-time multiplayer (shared presence and file sharing between different people) is scaffolded in the UI but not yet wired to a backend — the coworkers and shared features currently run locally.
