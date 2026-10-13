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
