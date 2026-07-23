# Froggie Weather — Art Inventory

Full map of the froggie weather art in the repo, so the widget (and we) never need to hit the GitHub API and risk rate limits.

## Source

- **Fork (primary):** https://github.com/ababab2222221/google-weather-icons
- **Original:** https://github.com/bignutty/google-weather-icons
- **Raw base URL:** `https://raw.githubusercontent.com/ababab2222221/google-weather-icons/main/froggie/v2/mobile`
- **Path in repo:** `froggie/v2/mobile` on branch `main`
- **CORS:** access-control-allow-origin: * (fetchable cross-origin)
- **License note:** Google weather art; personal use only, no clear redistribution license.

Any scene URL = `{raw_base}/{state}/{filename}`

## Counts

- **24 weather states**, **111 scene PNGs** total
- **2 states** have Lottie animations (the rest are static only)

## States

| State folder | Weather | Time | Scenes | Single? | Lottie |
|---|---|---|---|---|---|
| `00-neutral` | Neutral / fallback | any | 1 | yes |  |
| `01-sunny` | Sunny | day | 10 |  | yes |
| `02-mostly-sunny` | Mostly sunny | day | 10 |  | yes |
| `03-partly-cloudy-day` | Partly cloudy | day | 10 |  |  |
| `04-mostly-cloudy-day` | Mostly cloudy | day | 10 |  |  |
| `05-clear` | Clear | night | 6 |  |  |
| `06-mostly-clear` | Mostly clear | night | 6 |  |  |
| `07-partly-cloudy-night` | Partly cloudy | night | 5 |  |  |
| `08-mostly-cloudy-night` | Mostly cloudy | night | 5 |  |  |
| `09-cloudy` | Cloudy | any | 3 |  |  |
| `10-drizzle` | Drizzle | any | 5 |  |  |
| `11-rain` | Rain | any | 5 |  |  |
| `12-heavy-rain` | Heavy rain | any | 3 |  |  |
| `13-flurries` | Flurries | any | 2 |  |  |
| `15-snow-showers-snow` | Snow showers / snow | any | 3 |  |  |
| `16-blowing-snow` | Blowing snow | any | 1 | yes |  |
| `17-heavy-snow-blizzard` | Heavy snow / blizzard | any | 2 |  |  |
| `19-mixed-rain-hail-rain-sleet` | Mixed rain, hail, sleet | any | 2 |  |  |
| `20-rain-snow-wintry-mix` | Rain, snow, wintry mix | any | 1 | yes |  |
| `22-iso-thunderstorms` | Isolated thunderstorms | any | 3 |  |  |
| `23-scattered-thunderstorms` | Scattered thunderstorms | any | 4 |  |  |
| `24-strong-thunderstorms` | Strong thunderstorms | any | 4 |  |  |
| `25-breezy-windy` | Breezy / windy | any | 2 |  |  |
| `26-haze-fog-dust-smoke` | Haze, fog, dust, smoke | any | 8 |  |  |

## All scene files per state

### `00-neutral` — Neutral / fallback (1 scene)
- `00-neutral-fallback.png`

### `01-sunny` — Sunny (10 scenes)
- `01-sunny-beach-reading.png`
- `01-sunny-beach-sandcastle.png`
- `01-sunny-beach-sunscreen.png`
- `01-sunny-citypark-sunbathing.png`
- `01-sunny-creek-swimming.png`
- `01-sunny-field-kite.png`
- `01-sunny-hills-sunbathing.png`
- `01-sunny-home-laundry.png`
- `01-sunny-orchard-picking.png`
- `01-sunny-rooftop-pinacolada.png`
  - _Lottie:_ `sunny_background.json`, `sunny_foreground.json`

### `02-mostly-sunny` — Mostly sunny (10 scenes)
- `02-mostly-sunny-beach-reading.png`
- `02-mostly-sunny-beach-sandcastle.png`
- `02-mostly-sunny-beach-sunscreen.png`
- `02-mostly-sunny-citypark-picnic.png`
- `02-mostly-sunny-creek-swimming.png`
- `02-mostly-sunny-field-kite.png`
- `02-mostly-sunny-hills-sunbathing.png`
- `02-mostly-sunny-home-laundry.png`
- `02-mostly-sunny-orchard-picking.png`
- `02-mostly-sunny-rooftop-pinacolada.png`
  - _Lottie:_ `mostly_sunny_background.json`, `mostly_sunny_foreground.json`

### `03-partly-cloudy-day` — Partly cloudy (10 scenes)
- `03-partly-cloudy-day-beach-shells.png`
- `03-partly-cloudy-day-citypark-ukelele.png`
- `03-partly-cloudy-day-creek-feet.png`
- `03-partly-cloudy-day-field-biking.png`
- `03-partly-cloudy-day-field-hiking.png`
- `03-partly-cloudy-day-hills-painting.png`
- `03-partly-cloudy-day-hills-reading.png`
- `03-partly-cloudy-day-home-flowers.png`
- `03-partly-cloudy-day-orchard-butterflies.png`
- `03-partly-cloudy-day-orchard-treeswing.png`

### `04-mostly-cloudy-day` — Mostly cloudy (10 scenes)
- `04-mostly-cloudy-day-beach-shells.png`
- `04-mostly-cloudy-day-citypark-ukelele.png`
- `04-mostly-cloudy-day-creek-feet.png`
- `04-mostly-cloudy-day-field-biking.png`
- `04-mostly-cloudy-day-field-hiking.png`
- `04-mostly-cloudy-day-hills-painting.png`
- `04-mostly-cloudy-day-hills-reading.png`
- `04-mostly-cloudy-day-home-flowers.png`
- `04-mostly-cloudy-day-orchard-butterflies.png`
- `04-mostly-cloudy-day-orchard-treeswing.png`

### `05-clear` — Clear (6 scenes)
- `05-clear-creek-stars.png`
- `05-clear-field-lanterns.png`
- `05-clear-hills-camping.png`
- `05-clear-hills-telescope.png`
- `05-clear-home-lounging.png`
- `05-clear-orchard-fireflies.png`

### `06-mostly-clear` — Mostly clear (6 scenes)
- `06-mostly-clear-creek-stars.png`
- `06-mostly-clear-field-lanterns.png`
- `06-mostly-clear-hills-camping.png`
- `06-mostly-clear-hills-telescope.png`
- `06-mostly-clear-home-lounging.png`
- `06-mostly-clear-orchard-fireflies.png`

### `07-partly-cloudy-night` — Partly cloudy (5 scenes)
- `07-partly-cloudy-night-creek-fireflies.png`
- `07-partly-cloudy-night-field-fireflies.png`
- `07-partly-cloudy-night-hills-smores.png`
- `07-partly-cloudy-night-home-inside.png`
- `07-partly-cloudy-night-orchard-eating.png`

### `08-mostly-cloudy-night` — Mostly cloudy (5 scenes)
- `08-mostly-cloudy-night-creek-fireflies.png`
- `08-mostly-cloudy-night-field-fireflies.png`
- `08-mostly-cloudy-night-hills-smores.png`
- `08-mostly-cloudy-night-home-inside.png`
- `08-mostly-cloudy-night-orchard-eating.png`

### `09-cloudy` — Cloudy (3 scenes)
- `09-cloudy-hills-coffee.png`
- `09-cloudy-home-flowers.png`
- `09-cloudy-orchard-watching.png`

### `10-drizzle` — Drizzle (5 scenes)
- `10-drizzle-creek-leaf.png`
- `10-drizzle-field-leaf.png`
- `10-drizzle-hills-umbrella.png`
- `10-drizzle-home-laundry.png`
- `10-drizzle-orchard-reading.png`

### `11-rain` — Rain (5 scenes)
- `11-rain-creek-leaf.png`
- `11-rain-hills-umbrella.png`
- `11-rain-home-inside.png`
- `11-rain-home-laundry.png`
- `11-shower-rain-field-leaf.png`

### `12-heavy-rain` — Heavy rain (3 scenes)
- `12-heavy-rain-busstop-umbrella.png`
- `12-heavy-rain-cafe-sitting-singing.png`
- `12-heavy-rain-creek-leaf.png`

### `13-flurries` — Flurries (2 scenes)
- `13-flurries-citypark-snowman.png`
- `13-flurries-creek-iceskating.png`

### `15-snow-showers-snow` — Snow showers / snow (3 scenes)
- `15-snow-showers-snow-citypark-snowman.png`
- `15-snow-showers-snow-creek-iceskating.png`
- `15-snow-showers-snow-home-shoveling.png`

### `16-blowing-snow` — Blowing snow (1 scene)
- `16-blowing-snow-field-snowman.png`

### `17-heavy-snow-blizzard` — Heavy snow / blizzard (2 scenes)
- `17-heavy-snow-blizzard-home-inside.png`
- `17-heavy-snow-blizzard-home-shoveling.png`

### `19-mixed-rain-hail-rain-sleet` — Mixed rain, hail, sleet (2 scenes)
- `19-mixed-rain-hail-rain-sleet-busstop-waiting.png`
- `19-mixed-rain-hail-rain-sleet-cafe-entering.png`

### `20-rain-snow-wintry-mix` — Rain, snow, wintry mix (1 scene)
- `20-rain-snow-wintry-mix-citypark-snowman.png`

### `22-iso-thunderstorms` — Isolated thunderstorms (3 scenes)
- `22-iso-thunderstorms-busstop-newspaper.png`
- `22-iso-thunderstorms-cafe-looking-outside.png`
- `22-iso-thunderstorms-home-inside.png`

### `23-scattered-thunderstorms` — Scattered thunderstorms (4 scenes)
- `23-scattered-thunderstorms-busstop-coffee.png`
- `23-scattered-thunderstorms-busstop-newspaper.png`
- `23-scattered-thunderstorms-cafe-looking-outside.png`
- `23-scattered-thunderstorms-home-inside.png`

### `24-strong-thunderstorms` — Strong thunderstorms (4 scenes)
- `24-strong-thunderstorms-busstop-coffee.png`
- `24-strong-thunderstorms-busstop-newspaper.png`
- `24-strong-thunderstorms-cafe-looking-outside.png`
- `24-strong-thunderstorms-home-inside.png`

### `25-breezy-windy` — Breezy / windy (2 scenes)
- `25-breezy-windy-creek-pinwheel.png`
- `25-breezy-windy-home-laundry.png`

### `26-haze-fog-dust-smoke` — Haze, fog, dust, smoke (8 scenes)
- `26-haze-fog-dust-smoke-bridge.png`
- `26-haze-fog-dust-smoke-busstop-waiting.png`
- `26-haze-fog-dust-smoke-field-lantern.png`
- `26-haze-fog-dust-smoke-fruit-stand.png`
- `26-haze-fog-dust-smoke-hills-cocoa.png`
- `26-haze-fog-dust-smoke-mountain.png`
- `26-haze-fog-dust-smoke-pier.png`
- `26-haze-fog-dust-smoke-rooftop.png`
