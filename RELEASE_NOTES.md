# Release notes

## 1.1.0

Now on itch.io: https://meteori-k.itch.io/worldmaker

- New: time of day. A clock at the base meridian; every place lives its local hour. Temperature and sun height at dawn, noon, dusk and midnight, with the day and night range.
- New: tides change the climate in proportion to the time the land spends under water (cooler, more humid, rainier, less continental).
- New: orbit eccentricity and perihelion, so summers and winters are no longer equal.
- New: Holdridge+ (heat stress, best and worst season), Koppen polar class and hot-summer and late-winter suffixes, and a seasonal regime layer.
- New: per-tile metrics: sunshine hours, wet-bulb temperature, potential evapotranspiration, relative humidity, frost-free days.
- New: export the whole world as CSV or JSON (Pause menu), also as a download in the browser.
- New: altitude airbrushes (raise, lower, smooth) with soft edges and protected height ranges.
- Changed: a slowly rotating planet now spreads more heat toward the poles than a fast one (before, a 8-day and a 26-day planet gave the same result).

Built from the same code as Meteori-k Mapper 0.7.7.

## 1.0.1

- New: Import map (Pause menu, or Ctrl+Shift+I). Builds a whole world from a picture: a land/water mask, a grey height map, or a colour-coded hypsometric map (blue water, green to red altitude). Flat or Mercator pictures, adjustable grid detail, live preview, undoable with Ctrl+Z.
- Screenshots added to the README.

Built from the same code as Meteori-k Mapper 0.7.3.

## 1.0.0

First release of Meteorik WorldMaker, the free world-only edition.

- Planet and cosmos editor: star, size, mass, tilt, day and year, moons.
- Land, water, altitude, plates and biome painting.
- Climate simulation with circulation regimes, wind-carried moisture, rain shadows, ocean currents and thermal lag.
- Seasons, tides, rivers, snow and vegetation layers.
- Koppen and Holdridge biomes, extra biomes, resources per cell.
- Spanish and English interface.
- Windows build and a browser build (save and load through your browser's download and file picker).

Built from the same code as Meteori-k Mapper 0.7.2. The game features (countries, cities, turns, the world book and the AI narrator) are not included in this edition.
