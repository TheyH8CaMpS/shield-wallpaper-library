# Shield Wallpaper Library

A 23-image photographic collection for Projectivy Premium + Overflight on NVIDIA Shield TV: dark and vibrant green nature, Los Angeles, Dodgers, Raiders and Lakers.

## Current status

The `overflight.json` feed is committed. **Repository visibility is private right now**, so anonymous Shield access won't work until this repository is made public. No other repository should be altered. There are no actual photos stored here: the feed references external image URLs.

## First-time setup

1. Inspect this repository for anything sensitive, then change **this repository only** to Public under GitHub Settings → General → Danger Zone → Change repository visibility.
2. Open this URL in a signed-out/incognito browser to verify public access:
   https://raw.githubusercontent.com/TheyH8CaMpS/shield-wallpaper-library/main/overflight.json
3. Install **Overflight (Projectivy Plugin)** from Google Play on the Shield (Projectivy Premium required).
4. In Projectivy: Settings → Appearance → Wallpaper → Overflight, then open provider settings and set the custom JSON/media source URL to the raw link above.
5. Configure rotation and HTTP/media cache interval as desired. Refresh/restart the provider if edits aren't immediately visible.

## Maintain the collection

Edit `overflight.json` and append a record with `location`, `title`, `author` and `url_img`. Commit to `main`; the feed URL stays unchanged. Example:

```json
{"location":"Nature","title":"Forest","author":"Photographer","url_img":"https://example.com/forest.jpg"}
```

## Caveats

- Some Wikimedia Commons images are of sports teams. Verify each original image's license and its attribution conditions before redistributing or printing.
- Image URLs belong to the original hosts and could change. A request for 3840 × 2160 pixels is not a guarantee that the original contains native 4K detail.
- This repository does not contain photography binaries, secrets, app code, or files from the user's other projects.
- For a fully offline option, download and keep selected original full-resolution JPG files in a Shield folder, then use Projectivy's built-in user-defined folder wallpaper mode.
