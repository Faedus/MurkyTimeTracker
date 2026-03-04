# MurkyTime Tracker

A minimal browser-based time tracker built on the **MurkyTime** system by Luke Saunders (a.k.a. Murkdice).

No install. No build step. Open `murkytime.html` in any browser.

---

## What it is

MurkyTime is a tabletop RPG time-tracking system that divides the day into:

- **Turns** — 10 minutes each
- **Watches** — 6 hours, 36 Turns
- **Days** — 4 Watches (Morning, Afternoon, Evening, Night)

This tracker adapts that system for daily task management. The color shifts slowly across the day to simulate natural light. A focus check fires every 30 minutes as a gentle jolt to stay on task.

---

## How to use

| Element | What it shows |
|---|---|
| Watch title | Which 6-hour block you're in |
| `N/36` counter | Current Turn within the Watch |
| Ring fill | Progress through the current 10-minute Turn |
| Outer halo | Rest resource — drains over the Watch |
| Segments (16) | Watch progress in quarter-hour groups |
| Quarter dots | Which quarter of the Watch you're in |

### Focus Check
Every 30 minutes the UI jolts and displays **· focus check ·** — a prompt to re-engage with your current task.

### Rest / Break
The outer ring and bar track your rest resource, which depletes automatically over a full Watch (6 hours).

When it hits zero the UI desaturates to grey.

Click **Take a Break · 1 Turn** to start a 10-minute break. On completion, rest is fully restored and color returns.

---

## Running on GitHub Pages

1. Push `murkytime.html` to your repo
2. Go to **Settings → Pages → Source** and select your branch
3. Your tracker will be live at `https://yourusername.github.io/yourrepo/murkytime.html`

---

## Credits

Time system based on **MurkyTime** by Luke Saunders (a.k.a. Murkdice).  
Original pamphlet: [murkdice.itch.io](https://murkdice.itch.io/)

Fonts: [Cinzel](https://fonts.google.com/specimen/Cinzel) · [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts.
