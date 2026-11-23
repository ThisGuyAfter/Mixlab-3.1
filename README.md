# MixLab V3.1 - Sound Design & Mix Lab

Mobile-first Progressive Web App for FL Studio and general music production workflows.

## What's new in V3.1
- Fixes the recommendation gap: every legacy instrument-chain stage and every sound-recipe stage now surfaces stage-matched third-party plugin alternatives from the arsenal, with FL Studio stock choices shown only as optional fallbacks.
- Displays plugin tier, purpose and starting approach for each alternative.
- Keeps the original FL Studio suggestion visible for users who prefer stock tools.

## What's new in V3
- Retains the V2 instrument chain library, genre playbook, routing studio, plugin guide, troubleshooting and local notes/favorites.
- Adds 41 detailed sound-target recipes across vocals, drums, bass, keys, synths, guitars, orchestral and FX. Recipes include purpose, starting settings, why each stage sits where it does, plugin options and genre adaptation.
- Adds a plugin arsenal with 64 named tools across EQ, dynamics, de-essing, saturation, clipping, reverb, delay, modulation, pitch, synths, samplers, guitar amps, drums, meters and mastering.
- Labels free, paid, free-tier and included-with-FL Studio options; links to developer/product pages.
- Adds a custom chain builder with touch-friendly reorder arrows, desktop drag-and-drop, editable stages, plugin insertion, local saving and copy/export.
- Adds searchable/filterable sound recipes and plugin library.
- PWA metadata and offline service worker updated to V3.

## G-MEH library note
The G-MEH Windows library page loads its inventory dynamically. The page content available during research exposed the Windows Library heading and a plugin search field, but not the complete plugin catalogue. This app does not claim to contain a verified mirror of that catalogue. The arsenal is a curated shortlist of identifiable products with developer/product links. It is not an exhaustive G-MEH scrape. It does not provide cracked downloads, unauthorized installers or license-bypass instructions. Always check current licensing, format, compatibility and system requirements at the developer's official page.

## Research / catalogue references
- G-MEH Windows Library: https://g-meh.com/library/windows (catalogue is dynamically loaded; full list was not available in inspected page content).
- FreeAudioVST directory: https://freeaudiovst.com/ (free plugin discovery by category and platform).
- KVR Audio popularity and plugin databases: https://www.kvraudio.com/plugin-ranks.php and https://www.kvraudio.com/plugins/best-free-plugins/vst-plugins.
- Product links in the app point to developers or product pages where available. Pricing, free tiers and compatibility can change.

## Deploy free with GitHub Pages
1. Create a GitHub repository (e.g. `mixlab-v3`).
2. Upload all files in this folder to the repository root.
3. Open repository Settings -> Pages.
4. Choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Once published, open the HTTPS URL in Safari on your iPhone.
6. Tap Share -> Add to Home Screen -> Add.

HTTPS is required for service-worker offline caching. After the first successful visit, the core app files are cached. Favorites, notes and custom chains are stored locally in the browser on that device; they are not uploaded to a server. Clearing Safari website data may remove them.

## Updating
The service-worker cache name is `mixlab-v3-1-studio`. Increment it whenever you publish a future update.

## Important audio note
All settings are starting points, not fixed recipes. Plugin order depends on the source, performance, arrangement and intended aesthetic. Some stages are optional or parallel/send-based rather than serial inserts. Always level-match bypass, check mono compatibility and listen in context.
