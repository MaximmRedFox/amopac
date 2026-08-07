# AMOPAC — Training Simulation 01

Pac-Man, flipped. You command a colony of glowing AMO Strains, harvest
Signals (dots) with a single unified directional command, and stay clear
of RUG once a Pellet triggers a Signal Surge — RUG gets faster and can
eat your Strains for a while.

- 4 Strains, one shared direction command.
- Dots = Signals: +10 to you, −10 if RUG crosses one first.
- Pellets respawn periodically; anyone touching one — RUG or a Strain —
  triggers a Signal Surge (RUG hostile, +50% speed).
- A Strain eaten is gone for good.
- The colony visually mutates as its Signal count climbs.
- Local "Carrier ID" + Carrier Registry (a device-local leaderboard —
  not a real X/Twitter login, there's no backend here).
- Synthesized lab-style SFX via Web Audio, no external assets.

Single self-contained `index.html`, no build step, no dependencies.
Open it directly in a browser, or play it hosted via GitHub Pages.

Fan-made for fun. No original Pac-Man assets used — "RUG", "AMO" and
"TSL" are just in-simulation nicknames.
