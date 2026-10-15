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

Added Figure 4.3 (Interactive District Map Selection View) immediately after Figure 4.2 (trend), followed by Public Readiness 4.4 and About 4.5. Alert and notification sets are numbered 4.6–4.11; device versions are alternatives. Three new PNGs show the live homepage map with Quezon City selected, station risk coverage shading, the IDW-interpolated animated wind-particle trails and risk legend. Captures use the real October 15, 2026 forecast, not synthetic hazard values. Blue shading is selection. The existing frontend does not render a continuous filled heatmap; the figure caption explicitly distinguishes IDW wind flow from coverage shading and calibrated city forecast values. No product code or paper document was edited. Existing full-page images are reused without modification.


### Figure 4.3 wind animation capture update

Replaced all three map PNGs with frames of the original live wind-particle animation. Reduced-motion arrows were disabled for capture; no production animation code or design was changed. Capture checks confirm animation enabled and running, reduced motion off, and trails of 16 points on desktop and phone.


### Figure 4.3 ? City of Manila

Replaced the three spatial figure images with 2? resolution captures focused on the City of Manila and its 16 highlighted district boundaries. The existing system maps Manila to Sangley Point (Sector West/Bay, Manila Bay / SW Approach); that mapping and the displayed live forecast were preserved. The context capture includes risk, wind, pressure tendency, rainfall and humidity. Original wind-particle trails remain enabled. Website defaults and production source were not changed.


### Full-page Manila risk-tier thesis sample

Added desktop and phone whole-page views under `#thesis-manila-full-sample`, next to Figure 4.2 and before Figure 4.3. Manila is selected, mapped to Sangley Point, with one High trend day (71.0 km/h), Moderate days and Low days. Sample station data, trend cards, side panel, annual chart and Top 3 are rendered through the existing UI with controlled illustrative values. These are sample UI figures, not actual forecasts. Both include the footer and Back to top, with original wind trails and no production code changes. The phone retains native horizontal card scrolling.


### Manila sample corrected lead tags ? October 16, 2026

The five visible desktop trend cards now show Low (24.0), Moderate (51.0), High (74.0), Low (22.0), Low (28.0 km/h). Both desktop and phone captures were regenerated. Native card metadata and screenshots were checked: High shows Within 24 hrs, Moderate shows Within 36 hrs, and Low cards have no lead tags. Using the existing app gust factor 1.15, 74.0 / 1.15 exceeds PAGASA's Signal 2 sustained minimum of 62 km/h; 51.0 / 1.15 meets Signal 1's 39 km/h minimum. The 1.15 factor is application-specific, not a PAGASA standard. Official reference: https://pagasa.dost.gov.ph/learning-tools/tropical-cyclone-wind-signal . The scenario retains October 15 as its illustrative date. No production code was changed.


### Manila Today reference and native shorter trails

Updated desktop and phone full-page samples so Today matches the supplied Manila reference: Low, 11.0 km/h W, 1008.4 hPa (drop 1.5), rainfall 0.8 mm, humidity 84.0%. Tomorrow carries the High sample at 74.0 km/h with Within 24 hrs; Yesterday is Moderate at 51.0 with Within 36 hrs. The five visible desktop cards still contain one High, one Moderate and three Low. Today's three station winds are Low (9, 11 and 7 km/h), so the native map renderer naturally produces shorter green trails. The native 16-point trail setting and production code remain unchanged. Measured maximum trail lengths at capture: about 24.5 CSS px desktop and 20.4 CSS px phone. Footer and Back to top remain visible. These are illustrative thesis screenshots, not current forecasts.


### Additional Manila High / Pasay Moderate variant

Added six images under `#thesis-manila-pasay-alerts`: initial and expanded alerts plus matching notification illustrations for desktop and phone. Manila is High at 74.0 km/h (Sangley Point), Pasay is Moderate at 50.3 km/h (NAIA), matching the full-page sample's October 16 scenario. Both named pins and both city outlines were verified inside the alert map. Manila uses the website's 16 inline district geometries, preloaded into its existing boundary cache for capture; Caloocan is excluded. These are clearly identified thesis illustrations, not real warnings or delivered notifications. Existing gallery images and production source were not changed.


### Matching notification-card close-ups

Added Android and Windows notification-only crops for the Manila High (74.0 km/h) / Pasay Moderate (50.3 km/h) variant. Text was checked against the paired alert. Gallery captions continue to identify these as illustrations.


### Manila / Pasay variant date correction

Updated all eight alert and notification images to the illustrative forecast date Thursday, October 15, 2026, matching the supplied High-risk full-page reference. The headline and notification title say Today; date-dependent preparation text was regenerated. Initial and expanded alerts, device notification illustrations and cropped notification cards were recaptured. Manila remains High at 74.0 km/h and Pasay Moderate at 50.3 km/h. This date correction applies to this separate variant; production source and other figure sets are unchanged.


### Timing correction ? October 16, 2026

Recaptured all eight Manila High / Pasay Moderate alert and notification illustrations. The scenario forecast date remains Thursday, October 15, 2026, and the Android clock now shows 16:00 (4:00 PM Philippine time), matching the reference update time. Removed the unsupported midnight arrival-time assertion: daily forecasts do not specify an exact wind-arrival hour. Manila?s 24-hour and Pasay?s 36-hour values are reference warning lead times, not countdowns. See [PAGASA?s Tropical Cyclone Wind Signal guide](https://pagasa.dost.gov.ph/learning-tools/tropical-cyclone-wind-signal). These are thesis illustrations, not real warnings or delivered notifications. Production application code is unchanged.
