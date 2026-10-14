# Image sources — telavang-sales-bi-premium.html

All product photos were supplied directly by the user as screenshots taken from the official
site **telavang.com**, uploaded in this session and saved under `assets/<category>/raw/`
(full, uncropped screenshots, kept for provenance). This Claude session has no outbound
network access, so none of these images were fetched automatically — every one was given by
the user, who identified each as coming from the live telavang.com product pages.

The files actually embedded in the dashboard live under `assets/products/*.webp` — each is a
cropped (packaging only, UI chrome removed) and compressed copy of one `raw/` screenshot.

| Embedded file | Flavor / item | Source (raw screenshot) | Status |
|---|---|---|---|
| talabar-badam-zamini.webp | پروتئین بار بادام زمینی | assets/talabar/raw/badam-zamini.png | Official (telavang.com) |
| talabar-biscuit.webp | پروتئین بار بیسکوئیت | assets/talabar/raw/biscuit.png | Official |
| talabar-peste.webp | پروتئین بار پسته | assets/talabar/raw/peste.png | Official |
| talabar-sib-macha.webp | پروتئین بار سیب سبز ماچا | assets/talabar/raw/sib-macha.png | Official |
| talabar-shokolat-fandoghi.webp | پروتئین بار شکلات فندوقی | assets/talabar/raw/shokolat-fandoghi.png | Official |
| talabar-ghahve.webp | پروتئین بار قهوه | assets/talabar/raw/ghahve.png | Official |
| talabar-moz-chia.webp | پروتئین بار موز چیا | assets/talabar/raw/moz-chia.png | Official |
| talabar-mix-bari-chia.webp | پروتئین بار میکس بری چیا | assets/talabar/raw/mix-bari-chia.png | Official |
| talabar-nargil.webp | پروتئین بار نارگیلی | assets/talabar/raw/nargil.png | Official |
| tabdili-telawich.webp | تلاویچ (ساندویچ تخم‌مرغ) | assets/tabdili/raw/telawich-lineup.png | Official |
| tabdili-telaroll.webp | تلارول (سفیده پخته) | assets/tabdili/raw/telaroll-lineup.png | Official |
| tabdili-telara.webp | تلارا (سفیده پاستوریزه بطری) | assets/tabdili/raw/telara-lineup.png | Official |
| makian-kabk.webp | تخم کبک | assets/makian/raw/kabk-baldarchin.png | Official |
| makian-baldarchin.webp | تخم بلدرچین | assets/makian/raw/baldarchin.png | Official |
| egg-classic-9.webp | تخم مرغ کلاسیک ۹ عددی | assets/egg/raw/classic-9.png | Official |

## Not available / could not be verified

- Telavang sells eggs in several pack sizes (6/9/12/15-count etc.); only the ۹ عددی classic
  pack photo above was supplied and embedded so far — it stands in as the general تخم‌مرغ
  product image everywhere in the dashboard (filter thumbnail, gallery, hero collage, login
  shelf), not a claim about which specific pack size a given sale refers to.
- **Factory, production line, packaging-line, or distribution photography**: none were
  available (no network access to browse telavang.com's media/gallery pages, and none were
  supplied by the user). The dashboard's login-screen illustration and the product filter
  thumbnails use only the real product packaging photos above; the "factory journey" artwork
  on the login screen is an explicitly stylized, hand-built SVG graphic — captioned in the UI
  itself as illustrative, not a real photo of the line — so it is never mistaken for one.
- **Official Telavang videos**: none were found or embedded. No video content appears anywhere
  in the premium file.

## How they're used

- `assets/products/*.webp`: referenced directly (`<img src="assets/products/...">`) by (a) the
  "گالری محصولات" panel on the محصولات tab, and (b) small 18px thumbnails rendered inside the
  product-filter buttons (تلابار / تخم مرغ تبدیلی / تخم ماکیان) in the filter bar.
- `assets/*/raw/*.png`: not referenced by the dashboard; kept only as the original, unedited
  screenshots for provenance/audit.
