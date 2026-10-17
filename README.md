# swiperight-data

Public data endpoint for the [SwipeRight](https://github.com/itsmeshibintmz/swiperight) app.

## Files

| File | Purpose |
|---|---|
| `version.json` | Latest release info — the app polls this to check for updates |
| `cards.json` | Remote card database — reserved for future over-the-air card data updates |

## version.json format

```json
{
  "version": "1.4.7",
  "tag": "v1.4.7",
  "name": "Release title",
  "notes": "What changed in this version",
  "mac_url": "https://...SwipeRight-vX.Y.Z-mac.dmg",
  "android_url": "https://...SwipeRight-vX.Y.Z-android.apk"
}
```

Download links point to release assets attached to this repo's GitHub Releases.

---

*SwipeRight is a personal project — an Indian credit card reward optimizer for macOS and Android.*
