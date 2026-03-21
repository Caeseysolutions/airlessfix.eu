# AirlessFix — Changelog

## [4.0.0] — 2026-03-21

### Complete rebuild — AirlessFix v4

**Layout changes:**
- Website fully visible on load — no gate blocking content
- Model cards at top of page with HP, max tip, max L/min specs
- Each model card clickable → Marc opens pre-loaded for that model
- Feature cards clickable → Marc opens pre-loaded with that topic
- Marc as bottom-right chat widget (🔧 bubble)
- Registration triggered on first click — not blocking the page

**Marc behaviour:**
- Greets user by first name after registration
- Informal tone (du/tu/jij/tú) — never formal Sie/Vous
- First message always free — technical question counting starts after
- Ko-fi nudge after 5 technical questions — Marc keeps chatting after
- Ko-fi bar fully translated in all 5 languages
- Chat always scrolls to bottom — new messages anchor correctly
- Marc responses capped at 3 bullet points — short for painters on site

**Idle behaviour:**
- Marc bubble pulses after 5 seconds idle
- Bubble opens softly after 12 seconds with friendly message
- Language-aware peek message

**Repair partners:**
- Hardcoded from Excel files — no web search
- Format: Name · City · Phone only
- Address on request only
- NEVER customer IDs (internal data — never shared)
- Covers: BE, NL, DE, FR, AT, CH, GB, SE, ES, PT
- Always ends with AFX10 referral code

**Marc system prompt fixes:**
- NEVER quote prices for parts or labour
- NEVER refer to manufacturer by name
- Keep responses to 3 points max
- Service centre = "Repair Partners" throughout

**New pages:**
- /blog/how-to-prime-airless-sprayer.html
- /blog/airless-tip-size-guide.html
- /blog/winterising-airless-sprayer.html
- /blog/a100-troubleshooting.html
- /blog/airless-sprayer-safety.html
- /sitemap.xml

**SEO:**
- sitemap.xml submitted to Google Search Console
- All blog pages indexed with canonical URLs
- Structured data (JSON-LD) on homepage
- Internal linking between all blog pages and homepage
- Geo-filter: Europe + wide European neighbours only

**Infrastructure:**
- Cloudflare email routing: support@airlessfix.eu → airlessfixeu@gmail.com ✅
- Ko-fi webhook → Apps Script → PDF email → all 5 languages ✅
- Registration thank-you email → DriveAlert cross-sell (Apps Script URL to be added)

---

## [3.1.1] — 2026-03-20
- Logo "Fix" → orange (#efa400)
- Model card numbers (A20–A100) → orange

## [3.1.0] — 2026-03-20
- privacy.html added (GDPR + EU AI Act compliant)

## [3.0.0] — 2026-03-20
- Full AirlessFix site with Marc AI bot deployed
- Ko-fi pipeline live and tested
- 5 language support EN/NL/FR/DE/ES
