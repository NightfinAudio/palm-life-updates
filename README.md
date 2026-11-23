# Palm Life updates

Palm Life reads `version.json` once a day to see whether a newer version is out.

**To announce an update** (after uploading the new zip to Polar), edit `version.json`:

```json
{
  "latest": "1.0.1",
  "url": "https://polar.sh/nightfin/portal",
  "notes": "What changed, in one sentence."
}
```

- `latest`: the new version number (must be higher than what customers have).
- `url`: where the UPDATE button sends customers (your Polar customer portal).
- `notes`: shown in the plugin's update window.

Within a day, every copy of Palm Life shows **UPDATE TO 1.0.1**.
