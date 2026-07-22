# Froggie Weather

A cozy weather widget using the Google "froggie" weather art. Current temperature,
feels-like, today's high/low, condition, and a randomly-picked frog scene that matches
the weather and time of day. Tap the small circle in the bottom-right to shuffle to a
different scene for the same weather.

- **Data:** Open-Meteo (free, no API key).
- **Art:** bundled from `github.com/bignutty/google-weather-icons` (v2/mobile), so it keeps
  working even if that repo disappears. All 111 scene variants are packed into `index.html`.
- **Location:** remembers your last searched city (localStorage). GPS works too, but only
  over `https://` or `localhost` — a hosted page gets it; a raw local file does not.

## Files

```
index.html                 the whole widget (art bundled inline)
manifest.json              PWA manifest — makes it installable with the frog icon
sw.js                      service worker — opens offline after first load
icons/                     app icons (frog painter)
```

## Deploy on GitHub Pages

1. Commit all of these files to the repo root (keep the `icons/` folder).
2. Repo **Settings → Pages → Source: Deploy from a branch → main → / (root) → Save**.
3. Wait ~1 min. Your URL will be `https://YOURNAME.github.io/REPONAME/`
   (because the file is named `index.html`, no filename needed in the URL).

## Add to your Android home screen

1. Open the Pages URL in **Chrome** (Firefox on Android can't open local HTML, and Chrome
   handles the PWA install cleanly).
2. Search your city once — Chrome remembers it.
3. Chrome menu **⋮ → Add to Home screen → Add**. You get the frog icon, and it opens
   fullscreen with no address bar.

## Notes

- It's a tap-to-open fullscreen page, not a true live home-screen widget (Android live
  widgets need a native app). The icon + standalone launch is the closest no-APK option.
- To update the art or logic later, edit `index.html` and re-commit; bump `CACHE` in
  `sw.js` (e.g. `froggie-v2`) so the service worker fetches the new version.
