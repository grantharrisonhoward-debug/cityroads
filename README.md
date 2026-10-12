# City Roads

**[▶ Play City Roads](https://claude.ai/artifact/FLQFXTX6a4Fzii37LwmGAV)**. You can also open `index.html` in any browser. There's no build step.

A small city builder where traffic is the whole game, loosely inspired by *Trafficity*,
*Mini Motorways* and *Cities: Skylines*. A highway brings you into an empty valley with a river,
a lake and woodland. You draw the roads and paint where people live, shop and work. Neighbourhoods
lay themselves out, and every resident's commute has to get through the network you built.

## How it plays

- **Free-form roads.** Draw straight, curved (start, bend, end) or freehand roads anywhere.
  Roads at the same level join into junctions automatically.
- **Road designer.** Start from a preset (Street, One-way, Avenue, Boulevard, Freeway, Ramp), then
  fine-tune it:
  - Lanes ahead and back (0 back makes a one-way).
  - Median: none, painted, grass with trees, or concrete barrier.
  - Speed limit from 30 to 120 km/h.
  - Whether buildings may have driveways onto it.

  A live cross-section shows the result. **Upgrade** mode rebuilds an existing road with the current
  design, or reverses a one-way. Cars change lanes to overtake, so extra lanes add real capacity.
- **Elevation.** Build at tunnel, ground, bridge or high-bridge level. Roads only meet where they're
  at the same level, so you can stack interchanges and overpasses. Ramps form automatically where a
  road changes level. Bridges are drawn raised with pillars and shadows, and tunnels show as faint
  ghosts with portals.
- **Junctions are the bottleneck.**
  - At a yield junction, cars stop and only one direction moves at a time.
  - Traffic lights cycle between approaches (unlock at 60 residents).
  - Roundabouts keep several cars moving at once (unlock at 150).
- **Paint, don't place.** Brush homes, shops, industry and parks onto the land, or fill a whole area
  enclosed by roads. Zoning is free.
  - Lots fit themselves along every road inside the painted shape, rotated to face the street.
  - Larger painted areas get their own small access lanes and turning circles, so they fill in.
- **Procedural buildings.** Houses get hip or gable roofs, side wings, driveways, sheds, vegetable
  gardens, pools and back-yard trees. They grow into terraces and apartment blocks as land value rises.
  Shops become supermarkets and office towers, and industry becomes warehouses and smoking factories.
  Each building rises with a plot outline, dust and a springy pop-up animation.
- **Procedural parks.** Each painted park lays out paths from every road entrance to a fountain or
  gazebo, adds a pond with a promenade when it's big enough, and fills in trees, blossom trees,
  flowerbeds, benches, lamps and playgrounds, all growing in with a ripple.
- **Traffic decides everything.**
  - Cars plan routes around congestion, queue in lanes and wait at junctions.
  - Long commutes lower demand, cut tax income and eventually make residents abandon their homes.
  - The Traffic view shows jams, and red badges mark unhappy homes.

Your city saves automatically in your browser. Dark mode turns the map to night, with lit windows,
headlights and glowing park lamps.

## Controls

| Input | Action |
| --- | --- |
| Drag | Use the selected tool |
| Scroll / pinch | Zoom |
| Right-drag, Space-drag, two fingers, WASD | Pan |
| `1`–`5` | Inspect, Roads, Junctions, Zoning, Bulldoze |
| `Z` / `X` / `C` | Straight, curve or freehand road |
| Shift | Snap road angles to 15° |
| Space (tap) | Pause |
| Esc | Cancel the current road |
