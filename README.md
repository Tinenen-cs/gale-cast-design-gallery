# GALE-CAST design gallery

A picture gallery of the GALE-CAST website front-end design. It is **not** the working website: every image is a screenshot.

- View the gallery: https://tinenen-cs.github.io/gale-cast-design-gallery/
- The real website: https://gale-cast.vercel.app

Shows the current design (live since October 13, 2026), following the order of the GALE-CAST User Manual: whole pages, first-visit questions, every Home feature, the Gale Alert (High, Moderate, both, many areas, TEST ONLY survey alerts), notification settings, Public Readiness, About, offline and error screens, and the menu and footer. 324 pictures on desktop 1440, laptop 1366, tablet portrait 820 and landscape 1180, phone 390 and small phone 320, in light and dark. Whole pages and close-ups use the real GALE-CAST forecast at capture time; the alert pop-ups, the High and Moderate days and slow loading use sample data.

Captured October 13, 2026.

Latest local review: refreshed all 36 whole-page screenshots (six dimensions, both themes), with Back to top visible in the footer. Verified the button works on Home, Public Readiness and About. The phone chart and Top 3 panels are expanded for capture. Updated four loading/error screenshots after the no-saved-data skeleton fix. New captures show the local build awaiting deployment. Screenshot-only styling reveals the footer button while retaining the sticky header at the top; the working website is unchanged by capture styling.

Full-page footer audit: all 46 complete-page images include Back to top. This covers the 36 standard page/device/theme views, six High/Moderate/Low sample forecast-day views, and four loading/error views. Re-captured the six forecast-day views and verified the footer button works before capturing.

Added 24 actual initial-viewport alert screenshots: High, Moderate and combined High/Moderate, at desktop 1366, tablet 820, phone 390 and small phone 320, in both themes. Existing expanded alert images remain intact. Added six user-approved Android/Windows notification illustrations with actual app-generated sample text, paired with six actual website alert screenshots reached through notification forecast links. Illustrations are explicitly labeled and are not real OS captures or proof of live server push delivery. Service-worker click routing was checked for new, existing and unresponsive tabs; all six browser link-to-alert cases passed. All existing gallery image files were preserved.

Live alert references update (October 13, 2026): first-view and expanded High alerts come directly from ?galeAlert=TEST-MULTI; mixed High/Moderate alerts from TEST-MIXED; Moderate alerts from 2026-08-09. Captured directly on gale-cast.vercel.app, without API fixtures, across four device widths and both themes. The 2026-09-22 API currently returns an empty city list and therefore opens no alert; documented rather than substituted. The recent notification landing screenshots and illustration text use the same live references. Existing complete-page/footer screenshots remain unchanged. Expanded captures are labeled separately from normal first views. This supersedes the earlier local sample alert captures.



## Thesis alert and notification figures — October 15, 2026

Added 15 separate figures under `#thesis-alert-figures`: High for Quezon City only (68.4 km/h), Moderate for Manila only (44.1 km/h), and mixed High/Moderate for those two cities only. Each includes desktop and phone alert views, matching Windows/Android notification illustrations, and expanded phone alert content. The existing website renderer was used in browser memory with the built-in sample city values and October 16, 2026 as the illustrative forecast date. No TEST ONLY tag appears in these thesis figures. Gallery captions explicitly identify sample scenarios; they are not actual forecasts or proof of push delivery. Production website files and all prior gallery images are unchanged.


## Spatial map thesis figure — October 15, 2026

Added Figure 4.3 (Interactive District Map Selection View) immediately after Figure 4.2 (trend), followed by Public Readiness 4.4 and About 4.5. Alert and notification sets are numbered 4.6–4.11; device versions are alternatives. Three new PNGs show the live homepage map with Quezon City selected, station risk coverage shading, the IDW-interpolated wind-flow arrows and risk legend. Captures use the real October 15, 2026 forecast, not synthetic hazard values. Blue shading is selection. The existing frontend does not render a continuous filled heatmap; the figure caption explicitly distinguishes IDW wind flow from coverage shading and calibrated city forecast values. No product code or paper document was edited. Existing full-page images are reused without modification.
