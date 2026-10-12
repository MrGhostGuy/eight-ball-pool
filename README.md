# 8 Ball Pool

An original 8-ball pool game for the laptop. Play the CPU, sink your group,
then the 8 — and collect cues as you go.

## Play

https://mrghostguy.github.io/eight-ball-pool/

## Controls

| Input | Action |
|-------|--------|
| Move mouse | Aim |
| Hold **click** or **Space** | Build power |
| Release | Shoot |
| **S** / long-press side / two-finger tap | Swap marble |

After a foul you get **ball in hand** — move the mouse and click to place the
cue ball anywhere legal.

## Rules

- 15 object balls, 8 in the middle of the rack
- Break to claim a group: **solids (1–7)** or **stripes (9–15)**
- Pot your group, then the 8
- Fouls: scratch, no contact, hitting the wrong group first, or no rail after
  contact
- Pot the 8 early and you lose the rack
- A dry break re-racks

## Cues

You start with **Basic Oak**. Win a rack and you unlock a random cue:

| Tier | Chance |
|------|--------|
| Rare | 62% |
| Epic | 28% |
| Legendary | 10% |

Cues are stored in `localStorage`, so your collection persists between
sessions. Equip any unlocked cue from the **Cues** button — it shows on the cue
stick you aim with.

## Difficulty

Easy / Normal / Hard changes how much random aim error the CPU gets.

## Notes

Original code, art and sound — no copyrighted characters or music. Built as a
single self-contained HTML file; no build step, no dependencies.