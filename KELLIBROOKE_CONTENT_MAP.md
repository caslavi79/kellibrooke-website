# KELLIBROOKE CONTENT MAP — FULL SITE ARCHITECTURE

**Goal:** Outrank every Austin mortgage competitor through volume, specificity, and local authority. LendFriend has 220+ pages. We build 300+. Every page targets a real keyword, answers a real question, and funnels to a call.

**Rule:** All content must pass KELLIBROOKE_COMPLIANCE_RULES.md before publishing. No trigger terms on any page without proper /disclosures link.

---

## CURRENT SITE STRUCTURE

### Nav (all pages)
`Kellibrooke | Mortgage Partners` — `Scenarios` | `How It Works` (scroll) | `Loan Programs` | `About Me` | `(512) 350-9124`

### Page template
- Shared nav with logo (3 images: wordmark, line, mp), fly-in animations
- Shared footer: compliance (EHO logo, NMLS #2022197, individual NMLS #2025459, SML complaint, licensing disclosure, kellibrookemortgage.com)
- Cream background (#f8f5ef), golden globs, DM Serif Display + Outfit fonts
- Mobile: hamburger menu at 900px breakpoint
- Call/Text popup modal on all "Call or Text Me" buttons
- GitHub Pages hosted at caslavi79.github.io/kellibrooke-website/ (will move to custom domain)

### Built pages
| Page | Path | Status |
|------|------|--------|
| Homepage | `/index.html` | **LIVE** — full content, hero, stats, expertise cards, about, testimonials, how it works, differentiators, programs, market, CTA |
| Scenarios | `/expertise/index.html` | **PLACEHOLDER** — nav says "Scenarios", page title "Scenarios I Handle" |
| Loan Programs | `/programs/index.html` | **PLACEHOLDER** |
| About Me | `/about/index.html` | **PLACEHOLDER** |
| Contact | `/contact/index.html` | **BUILT** — call/text CTAs, full scenario form with chip selectors (purpose, program, term, down payment, stage) |

### Assets in repo
- Logo images: kellibrooke_wordmark.png, kellibrooke_line.png, kellibrooke_mp.png, kellibrookelogo.png
- headshot.JPG (Case portrait)
- og-image.jpg (social share: logo on golden glob background, 1200x630)
- equal-housing-opportunity-logo-1200w.png
- atxdrone.mp4 (66MB, background video)
- clients.mp4 (92MB, testimonial video in modal)

### Form backend
- Contact form markup ready, Formspree placeholder in action attribute
- Will be wired to Supabase + Resend
- Honeypot spam blocking + email validation planned

---

## TIER 0 — CORE PAGES (build first, launch with these)

### Homepage
- `/` — "Austin TX Mortgage Broker | Kellibrooke Mortgage Partners" — **LIVE**

### Scenarios (was "Expertise")
- `/expertise/` — "Scenarios I Handle | Kellibrooke Mortgage Partners" — **PLACEHOLDER, needs buildout**

### Loan Programs
- `/programs/` — "Loan Programs | Kellibrooke Mortgage Partners" — **PLACEHOLDER, needs buildout**

### About
- `/about/` — "About Case Laviolette | Austin Mortgage Broker" — **PLACEHOLDER, needs buildout**

### Contact
- `/contact/` — "Contact Kellibrooke | Call, Text, or Send Your Scenario" — **BUILT, needs backend**

### Legal / Compliance
- `/privacy-policy/` — GLBA-compliant privacy notice (CFPB model form)
- `/disclosures/` — Full TILA disclosure tables for any pages using trigger terms
- `/licensing/` — State licensing info, NMLS links, SML complaint notice

---

## TIER 1 — SERVICE PAGES (13 loan program silos, build within 30 days)

Each page: 1,500-2,500 words. What it is, who it's for, how Case handles it, safe language only, CTA to call.

### Purchase Loans
- `/conventional-loans-austin-tx/` — "Conventional Loans in Austin TX"
- `/fha-loans-austin-tx/` — "FHA Loans in Austin TX | First-Time Buyer Friendly"
- `/va-loans-austin-tx/` — "VA Loans in Austin TX | Zero Down, No PMI"
- `/usda-loans-austin-tx/` — "USDA Loans Near Austin TX | Rural Eligibility Guide"
- `/jumbo-loans-austin-tx/` — "Jumbo Loans in Austin TX | Above $832,750"

### Specialty Loans
- `/self-employed-mortgage-austin-tx/` — "Self-Employed Mortgage Broker Austin TX"
- `/bank-statement-loans-austin-tx/` — "Bank Statement Loans Austin TX | No Tax Returns"
- `/dscr-loans-austin-tx/` — "DSCR Investor Loans Austin TX"
- `/investment-property-loans-austin-tx/` — "Investment Property Mortgage Austin TX"

### Refinance
- `/refinance-austin-tx/` — "Refinance Your Mortgage in Austin TX"
- `/cash-out-refinance-austin-tx/` — "Cash-Out Refinance Austin TX"

### Construction / Specialty
- `/construction-loans-austin-tx/` — "Construction Loans Austin TX"
- `/renovation-loans-austin-tx/` — "FHA 203k & Renovation Loans Austin TX"

---

## TIER 2 — LOCATION PAGES (33 suburb/city pages, build within 60 days)

Each page: 1,000-1,500 words. Local market data, median price, property tax rate, school district, neighborhoods, why people move there, loan programs relevant to that price range. CTA to call.

**NO competitor has dedicated suburb pages. This is the single fastest SEO win.**

### Austin Metro Core
- `/mortgage-lender-austin-tx/` — primary city page
- `/mortgage-lender-south-austin-tx/`
- `/mortgage-lender-north-austin-tx/`
- `/mortgage-lender-east-austin-tx/`
- `/mortgage-lender-west-austin-tx/`

### Williamson County
- `/mortgage-lender-round-rock-tx/`
- `/mortgage-lender-cedar-park-tx/`
- `/mortgage-lender-georgetown-tx/`
- `/mortgage-lender-leander-tx/`
- `/mortgage-lender-hutto-tx/`
- `/mortgage-lender-liberty-hill-tx/`
- `/mortgage-lender-taylor-tx/`

### Travis County Suburbs
- `/mortgage-lender-pflugerville-tx/`
- `/mortgage-lender-manor-tx/`
- `/mortgage-lender-lakeway-tx/`
- `/mortgage-lender-bee-cave-tx/`
- `/mortgage-lender-westlake-hills-tx/`

### Hays County
- `/mortgage-lender-dripping-springs-tx/`
- `/mortgage-lender-kyle-tx/`
- `/mortgage-lender-buda-tx/`
- `/mortgage-lender-san-marcos-tx/`
- `/mortgage-lender-wimberley-tx/`

### Bastrop / Caldwell
- `/mortgage-lender-bastrop-tx/`
- `/mortgage-lender-elgin-tx/`
- `/mortgage-lender-lockhart-tx/`

### Other Texas Cities (expand reach)
- `/mortgage-lender-san-antonio-tx/`
- `/mortgage-lender-houston-tx/`
- `/mortgage-lender-dallas-tx/`
- `/mortgage-lender-fort-worth-tx/`
- `/mortgage-lender-new-braunfels-tx/`
- `/mortgage-lender-waco-tx/`
- `/mortgage-lender-killeen-tx/`
- `/mortgage-lender-temple-tx/`
- `/mortgage-lender-college-station-tx/`

---

## TIER 3 — FIRST-TIME BUYER CENTER (pillar content, build within 90 days)

### Main Hub
- `/first-time-home-buyer-austin-tx/` — Pillar page, 3,000+ words, links to all sub-pages

### Sub-Pages
- `/first-time-buyer/how-much-house-can-i-afford-austin/`
- `/first-time-buyer/down-payment-assistance-austin-tx/` — TSAHC, TDHCA, City of Austin programs
- `/first-time-buyer/closing-costs-explained-texas/`
- `/first-time-buyer/mortgage-pre-approval-guide/`
- `/first-time-buyer/fha-vs-conventional-which-is-better/`
- `/first-time-buyer/credit-score-needed-to-buy-a-home/`
- `/first-time-buyer/how-much-down-payment-do-i-need/`
- `/first-time-buyer/property-taxes-in-texas-explained/`
- `/first-time-buyer/homeowners-insurance-texas/`
- `/first-time-buyer/what-to-expect-at-closing/`
- `/first-time-buyer/mistakes-first-time-buyers-make/`
- `/first-time-buyer/renting-vs-buying-austin-2026/`
- `/first-time-buyer/how-to-choose-a-mortgage-broker/`
- `/first-time-buyer/mortgage-broker-vs-bank/`
- `/first-time-buyer/what-is-pmi-and-how-to-avoid-it/`
- `/first-time-buyer/earnest-money-explained/`

---

## TIER 4 — SELF-EMPLOYED / COMPLEX INCOME CENTER

### Main Hub
- `/self-employed-mortgage-guide/` — Pillar page

### Sub-Pages
- `/self-employed/bank-statement-loans-explained/`
- `/self-employed/how-lenders-calculate-self-employed-income/`
- `/self-employed/k1-income-mortgage-guide/`
- `/self-employed/1099-mortgage-options/`
- `/self-employed/profit-and-loss-only-loans/`
- `/self-employed/llc-mortgage-guide/`
- `/self-employed/tax-write-offs-hurt-your-mortgage/`
- `/self-employed/two-years-self-employment-myth/`
- `/self-employed/rsu-income-mortgage-austin/`
- `/self-employed/commission-income-mortgage/`
- `/self-employed/freelancer-mortgage-guide/`
- `/self-employed/business-owner-mortgage-checklist/`

---

## TIER 5 — INVESTOR / DSCR CENTER

### Main Hub
- `/real-estate-investor-mortgage-guide/` — Pillar page

### Sub-Pages
- `/investor/dscr-loans-explained/`
- `/investor/no-income-verification-investment-loans/`
- `/investor/how-many-investment-properties-can-i-finance/`
- `/investor/cash-out-refinance-investment-property/`
- `/investor/short-term-rental-mortgage/`
- `/investor/house-hacking-austin-tx/`
- `/investor/fix-and-flip-loans-austin/`
- `/investor/1031-exchange-and-financing/`
- `/investor/portfolio-restructuring-guide/`
- `/investor/austin-rental-market-analysis/`
- `/investor/multifamily-loans-austin-tx/`

---

## TIER 6 — VA LOAN CENTER

### Main Hub
- `/va-loans-texas/` — Pillar page

### Sub-Pages
- `/va-loans/va-loan-eligibility-guide/`
- `/va-loans/va-funding-fee-explained/`
- `/va-loans/va-loan-vs-conventional/`
- `/va-loans/va-loan-limits-texas-2026/`
- `/va-loans/va-irrrl-streamline-refinance/`
- `/va-loans/va-cash-out-refinance/`
- `/va-loans/va-loan-for-second-home/`
- `/va-loans/va-loan-closing-costs/`
- `/va-loans/va-loan-austin-neighborhoods/`
- `/va-loans/va-loan-with-bad-credit/`
- `/va-loans/va-loan-for-condos/`

---

## TIER 7 — REFINANCE CENTER

### Main Hub
- `/refinance-guide-texas/` — Pillar page

### Sub-Pages
- `/refinance/rate-and-term-refinance-explained/`
- `/refinance/cash-out-refinance-guide/`
- `/refinance/refinance-break-even-calculator/`
- `/refinance/when-should-i-refinance/`
- `/refinance/refinance-closing-costs-texas/`
- `/refinance/can-i-refinance-with-bad-credit/`
- `/refinance/fha-streamline-refinance/`
- `/refinance/debt-consolidation-refinance/`
- `/refinance/remove-pmi-through-refinance/`
- `/refinance/refinance-investment-property/`

---

## TIER 8 — AUSTIN MARKET EDUCATION HUB

### Main Hub
- `/austin-housing-market/` — Updated monthly, market snapshot

### Market Data Pages
- `/austin-market/median-home-prices-by-zip-code/`
- `/austin-market/property-tax-rates-by-county/`
- `/austin-market/austin-real-estate-forecast-2026/`
- `/austin-market/best-neighborhoods-for-first-time-buyers/`
- `/austin-market/austin-vs-san-antonio-housing-comparison/`
- `/austin-market/cost-of-living-austin-2026/`
- `/austin-market/mud-pid-districts-austin-explained/`
- `/austin-market/hoa-costs-austin-neighborhoods/`
- `/austin-market/new-construction-vs-existing-homes-austin/`

### Rate Education
- `/austin-market/what-drives-mortgage-rates/`
- `/austin-market/treasury-futures-and-mortgage-rates/`
- `/austin-market/dollar-index-and-mortgage-rates/`
- `/austin-market/how-to-read-mortgage-rate-trends/`
- `/austin-market/fed-rate-vs-mortgage-rate-difference/`
- `/austin-market/when-will-mortgage-rates-drop/`
- `/austin-market/rate-lock-strategy-guide/`

---

## TIER 9 — COMPARISON / VS PAGES (high intent)

- `/compare/mortgage-broker-vs-bank/`
- `/compare/fha-vs-conventional/`
- `/compare/fha-vs-va/`
- `/compare/fixed-vs-adjustable-rate/`
- `/compare/15-year-vs-30-year-mortgage/`
- `/compare/pre-approval-vs-pre-qualification/`
- `/compare/primary-residence-vs-investment-property-loans/`
- `/compare/jumbo-vs-conforming-loans/`
- `/compare/conventional-vs-portfolio-loans/`
- `/compare/buying-vs-renting-austin-2026/`

---

## TIER 10 — FAQ / "PEOPLE ALSO ASK" PAGES (55 questions)

Each page: 500-800 words answering one specific question. Fast to produce, targets PAA boxes.

### Buying
- `/faq/how-much-do-i-need-to-buy-a-house-in-austin/`
- `/faq/can-i-buy-a-house-with-no-down-payment-in-texas/`
- `/faq/what-credit-score-do-i-need-to-buy-a-house-in-texas/`
- `/faq/how-long-does-it-take-to-close-on-a-house-in-texas/`
- `/faq/can-i-buy-a-house-while-self-employed/`
- `/faq/can-i-use-gift-money-for-a-down-payment/`
- `/faq/what-happens-if-appraisal-comes-in-low/`
- `/faq/do-i-need-a-realtor-to-buy-a-house/`
- `/faq/what-is-earnest-money-in-texas/`
- `/faq/how-much-are-closing-costs-in-texas/`
- `/faq/can-i-buy-a-house-with-student-loans/`
- `/faq/what-is-a-mortgage-contingency/`
- `/faq/can-seller-pay-my-closing-costs-in-texas/`
- `/faq/what-does-under-contract-mean/`
- `/faq/how-do-property-taxes-work-in-texas/`
- `/faq/what-is-a-mud-district-in-texas/`
- `/faq/what-is-a-pid-in-texas/`
- `/faq/how-much-is-homeowners-insurance-in-austin/`

### Rates
- `/faq/what-are-mortgage-rates-today-in-austin/`
- `/faq/will-mortgage-rates-go-down-in-2026/`
- `/faq/how-do-i-get-the-lowest-mortgage-rate/`
- `/faq/what-is-apr-vs-interest-rate/`
- `/faq/should-i-buy-points-to-lower-my-rate/`
- `/faq/should-i-lock-my-rate-now-or-wait/`
- `/faq/how-does-the-fed-affect-mortgage-rates/`
- `/faq/what-is-a-rate-lock/`
- `/faq/can-i-negotiate-my-mortgage-rate/`

### Qualifying
- `/faq/how-much-mortgage-can-i-qualify-for/`
- `/faq/what-is-debt-to-income-ratio/`
- `/faq/can-i-get-a-mortgage-with-a-500-credit-score/`
- `/faq/how-far-back-do-lenders-look-at-bank-statements/`
- `/faq/do-lenders-verify-employment-before-closing/`
- `/faq/can-i-get-a-mortgage-after-bankruptcy/`
- `/faq/can-i-get-a-mortgage-after-foreclosure/`
- `/faq/can-i-get-a-mortgage-with-a-tax-lien/`
- `/faq/can-i-get-a-mortgage-during-a-job-change/`
- `/faq/what-documents-do-i-need-for-a-mortgage/`

### Refinancing
- `/faq/is-it-worth-refinancing-right-now/`
- `/faq/how-much-does-it-cost-to-refinance-in-texas/`
- `/faq/can-i-refinance-with-no-closing-costs/`
- `/faq/how-soon-can-i-refinance-after-buying/`
- `/faq/can-i-refinance-if-i-owe-more-than-my-home-is-worth/`
- `/faq/what-is-a-cash-out-refinance/`
- `/faq/can-i-refinance-to-remove-my-ex-from-the-mortgage/`

### Self-Employed
- `/faq/can-i-get-a-mortgage-with-one-year-self-employment/`
- `/faq/what-is-a-bank-statement-loan/`
- `/faq/do-lenders-use-gross-or-net-income-for-self-employed/`
- `/faq/can-i-write-off-too-much-to-qualify-for-a-mortgage/`
- `/faq/what-is-a-profit-and-loss-statement-for-mortgage/`

### VA
- `/faq/am-i-eligible-for-a-va-loan/`
- `/faq/can-i-use-my-va-loan-more-than-once/`
- `/faq/do-i-have-to-pay-the-va-funding-fee/`
- `/faq/can-a-surviving-spouse-use-a-va-loan/`
- `/faq/can-i-use-a-va-loan-for-investment-property/`

### Investors
- `/faq/how-many-rental-properties-can-i-finance/`
- `/faq/what-is-a-dscr-loan/`
- `/faq/can-i-use-rental-income-to-qualify-for-a-mortgage/`
- `/faq/what-is-the-minimum-down-payment-for-investment-property/`
- `/faq/can-i-house-hack-with-an-fha-loan/`

---

## TIER 11 — TOOLS & CALCULATORS (interactive, high-value)

- `/calculator/mortgage-payment-calculator/`
- `/calculator/affordability-calculator/`
- `/calculator/refinance-break-even-calculator/`
- `/calculator/rent-vs-buy-calculator/`
- `/calculator/closing-cost-estimator-texas/`
- `/calculator/dti-calculator/`
- `/calculator/property-tax-calculator-texas/`

---

## TIER 12 — BLOG / SEASONAL / TOPICAL (ongoing, 2-4 per month)

### Annual Updates
- `/blog/texas-conforming-loan-limits-2026/`
- `/blog/fha-loan-limits-texas-2026/`
- `/blog/austin-housing-market-forecast-2026/`
- `/blog/best-time-to-buy-a-home-in-austin/`
- `/blog/property-tax-rates-texas-2026/`
- `/blog/texas-homestead-exemption-guide-2026/`

### Evergreen Education
- `/blog/complete-guide-to-buying-a-home-in-texas/`
- `/blog/how-to-improve-your-credit-score-fast/`
- `/blog/understanding-your-loan-estimate/`
- `/blog/understanding-your-closing-disclosure/`
- `/blog/what-your-mortgage-lender-isnt-telling-you/`
- `/blog/the-real-cost-of-waiting-to-buy/`
- `/blog/how-to-budget-for-a-home-purchase/`
- `/blog/what-to-do-after-you-close-on-your-home/`
- `/blog/how-escrow-works-in-texas/`
- `/blog/title-insurance-explained/`
- `/blog/survey-requirements-in-texas/`
- `/blog/texas-community-property-and-mortgages/`
- `/blog/how-divorce-affects-your-mortgage/`
- `/blog/how-marriage-affects-your-mortgage/`
- `/blog/buying-a-home-as-a-non-citizen-in-texas/`
- `/blog/itin-loans-in-texas/`

### Market Commentary
- `/blog/what-tariffs-mean-for-mortgage-rates/`
- `/blog/fed-meeting-recap-[month]-2026/`
- `/blog/bond-market-weekly-[date]/`
- `/blog/austin-market-update-[month]-2026/`
- `/blog/why-your-mortgage-rate-isnt-what-the-news-says/`

### Neighborhood Guides
- `/blog/buying-in-[neighborhood]-austin-what-to-know/` — 20+ neighborhoods:
  Mueller, East Austin, South Congress, Barton Hills, Zilker, Travis Heights,
  Domain/North Burnet, Arboretum, Great Hills, Northwest Hills,
  Circle C, Shady Hollow, Avery Ranch, Brushy Creek,
  Steiner Ranch, River Place, Rough Hollow, Serene Hills,
  Crystal Falls, Travisso, Rancho Sienna

---

## TIER 13 — LANDING PAGES (paid traffic / campaign specific)

- `/get-pre-approved/`
- `/va-loan-pre-approval/`
- `/self-employed-pre-approval/`
- `/investor-loan-quote/`
- `/refinance-analysis/`
- `/rate-alert-signup/`

---

## TIER 14 — NEWSLETTER / RATE ALERT SYSTEM

- `/subscribe/` — Main signup page
- Rate alert emails (when rates drop to trigger points)
- Monthly market update email
- New blog post notifications
- Program announcements (new DPA programs, limit changes)

---

## CONTENT PRODUCTION SCHEDULE

### Month 1 (Launch)
- Tier 0: All core pages (5 pages) — **PARTIALLY DONE**
- Tier 1: Top 6 service pages (conventional, FHA, VA, self-employed, refinance, jumbo)
- Tier 11: Mortgage payment calculator + affordability calculator

### Month 2
- Tier 1: Remaining 7 service pages
- Tier 2: Top 10 location pages (Round Rock, Cedar Park, Georgetown, Pflugerville, Leander, Kyle, Buda, Lakeway, Dripping Springs, Bastrop)
- Tier 3: First-time buyer hub + 5 sub-pages

### Month 3
- Tier 2: Remaining location pages
- Tier 3: Remaining first-time buyer sub-pages
- Tier 8: Market education hub + rate explainers
- Tier 12: First 4 blog posts

### Month 4-6
- Tier 4: Self-employed center (13 pages)
- Tier 5: Investor center (12 pages)
- Tier 6: VA center (12 pages)
- Tier 9: 5 comparison pages
- Tier 10: 20 FAQ pages
- Tier 12: 8 blog posts

### Month 6-12
- Tier 7: Refinance center (11 pages)
- Tier 10: Remaining 35 FAQ pages
- Tier 12: 2-4 blog posts per month
- Tier 2: Texas cities outside Austin (9 pages)
- Neighborhood guides (20 posts)

### Ongoing
- Monthly market updates
- Rate alert emails when significant moves happen
- Annual updates to loan limits, tax rates, forecasts
- New FAQ pages based on Google Search Console query data

---

## TOTAL PAGE COUNT

| Tier | Category | Pages |
|------|----------|-------|
| 0 | Core | 6 |
| 1 | Service/Loan Programs | 13 |
| 2 | Location Pages | 33 |
| 3 | First-Time Buyer | 17 |
| 4 | Self-Employed | 13 |
| 5 | Investor/DSCR | 12 |
| 6 | VA Loans | 12 |
| 7 | Refinance | 11 |
| 8 | Market Education | 17 |
| 9 | Comparison Pages | 10 |
| 10 | FAQ / PAA | 55 |
| 11 | Calculators | 7 |
| 12 | Blog / Seasonal | 40+ |
| 13 | Landing Pages | 6 |
| 14 | Newsletter | 1 |
| **TOTAL** | | **253+ pages** |

With ongoing blog posts at 2-4/month, you hit 300+ within the first year.

---

## SEO RULES FOR ALL CONTENT

1. Every page has a unique H1 with primary keyword
2. Every page has a unique meta title (60 chars) and meta description (155 chars)
3. URL structure: lowercase, hyphens, includes city + state where relevant
4. Internal linking: every page links to at least 3 other relevant pages
5. CTA on every page: "Call or Text Me" popup with phone number + "Send Me Your Scenario" to /contact/
6. NMLS #2022197 + individual NMLS #2025459 (when Case is featured) + EHO logo in footer of every page
7. Schema markup: LocalBusiness on all, FAQPage on FAQ pages, LoanOrCredit where applicable
8. Images: descriptive alt text with keywords, compressed, WebP format
9. Mobile-first: hamburger menu at 900px, all content readable on phone
10. Page speed: target < 3 second load time, lazy-load videos
11. Canonical URLs set on every page
12. Sitemap.xml and robots.txt properly configured
13. All pages use shared nav/footer template matching current homepage framework
14. Call/Text popup modal on all primary CTA buttons
15. All content checked against KELLIBROOKE_COMPLIANCE_RULES.md and Kellibrooke_Advertising_Marketing_Policy.docx before publishing
