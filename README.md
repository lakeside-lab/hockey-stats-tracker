# 🏒 Hockey Stats Tracker

A free, iPhone-first web app for tracking hockey game stats live at the rink — built for volunteer stat-keepers at non-profit teams.

**Live app:** https://lakeside-lab.github.io/hockey-stats-tracker/

No account, no cost, no app-store download. Open the link in Safari, add it to your Home Screen, and it behaves like a native app — it even works when the rink wifi doesn't, and all your data stays saved on your phone.

---

## Quick start

1. Open https://lakeside-lab.github.io/hockey-stats-tracker/ in Safari on your iPhone.
2. Tap **Share → Add to Home Screen** so it's one tap away on game day.
3. Load it once on wifi before heading to the rink — after that it works offline.

---

## Guide 1 — Set up your team and roster

1. On the home screen, type your team name and tap **Add**.
2. Tap the team to open it, then go to the **Roster** tab.
3. Add each player by **jersey number** and name, then tap **Add**. Players are sorted by number.

> **Why numbers?** In a fast game you can't read names — but you can read the big number on a jersey. During games you tap the number, never the name, so tracking keeps up with the play. Set the roster up once at the start of the season and you're done.

You can rename the team with the ✏️ button, and edit or delete players from the roster list at any time.

## Guide 2 — Choose which events to track

Not every team wants the full stat sheet. On your team's **Events** tab you'll see a checklist of everything the app can track:

Goal · Assist · Shot on net · Missed shot · Blocked shot · Save · Pass · Penalty · Faceoff won · Faceoff lost · Hit · Takeaway · Giveaway

Tick only what your team cares about. Only ticked events appear as big buttons during a live game, so the screen stays clean and fast. Each team has its own set — a team that doesn't track passes simply leaves it unticked.

## Guide 3 — Track a live game

1. On your team's **Games** tab, enter the opponent name (date defaults to today) and tap **Start new game**.
2. The live screen shows the score, a period selector (**1st / 2nd / 3rd / OT**), and big buttons for your team's enabled events.
3. To record something: tap the event (e.g. 🥅 Goal), then tap the player's **jersey number** in the picker. That's it — two taps.
   - For a goal, you'll get an optional **"Assist by?"** step — pick the number or tap Skip.
4. Mis-tapped? Hit **↩ Undo last event**, or delete any single row in the event log.
5. The **Running totals** table and **Event log** update live as you go.
6. When the game ends, tap **End game → report**.

> Tip: switch the period selector as the game moves along so every event is tagged with the right period.

## Guide 4 — Share the stats with coaches

After ending a game you land on the **Game report**: final score, a per-player table (one column per tracked event), and team totals.

Under **Share with coaches** you have three options:

- **Share…** — opens the iPhone share sheet with a plain-text summary. Send it by text, email, or AirDrop straight to the coaches.
- **Copy summary** — copies the same text so you can paste it into WhatsApp or anywhere else.
- **Download CSV** — saves a spreadsheet of the full event log plus per-player totals for anyone who wants to dig deeper.

## Guide 5 — Managing teams, games, and data

- **Multiple teams:** add as many teams as you like from the home screen — each keeps its own roster, event set, and game history.
- **Past games:** every game stays in the team's Games tab. Tap one to re-open its report; delete old ones you don't need.
- **Where's my data?** Everything is stored privately on your own phone (in the browser) — nothing is uploaded anywhere. That also means stats don't sync between devices: use the same iPhone all season.
- **Starting fresh:** clearing your browser's website data will erase the stats, so export anything important (CSV) at season's end.

---

## For developers

Single self-contained `index.html` — no build step, no dependencies, no external assets. To update the live site, replace `index.html` at the repo root; GitHub Pages serves it automatically.
