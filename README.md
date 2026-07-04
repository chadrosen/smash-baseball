# ⚾ Smash Baseball

A two-player baseball game built for the browser, no install or build step required — just open `index.html`.

**Play it live:** https://chadrosen.github.io/smash-baseball/

## How to play

One player pitches, the other bats.

| Action | Key |
| --- | --- |
| Pitch (hold to charge up speed, release to throw) | **Right Shift** |
| Swing | **Left Shift** |

- Hold Right Shift to wind up a pitch — the longer you hold it, the faster it comes in (capped so it's always hittable).
- Swing with good timing for a hit; miss the timing window and it's a strike.
- Balls and strikes work like real baseball: 3 strikes is an out, 4 balls is a walk.
- Outfielders can catch fly balls for an out if it lands in their catch radius; anywhere else is a hit.
- Hit it far enough to clear the fence for a home run — clear it with the bases loaded for a grand slam.
- First team to 20 runs wins.

## Features

- Two full 9-player lineups (Benjy and Ellie lead off their own teams; the other 8 spots are randomly drawn each game)
- Animated pitcher, batter, catcher, and outfielders
- A crowd, press box, and dugouts for atmosphere
- A running game log tracking every play
- A settings panel to rename teams/players and recolor jerseys
- Players occasionally crack jokes between pitches

## Configuring

Use the **⚙ Game Settings** panel (below the Restart button) to rename each team, rename Benjy/Ellie, and change team colors.

## Tech

Single self-contained `index.html` — plain HTML, CSS, and JavaScript, no dependencies, no build step.
