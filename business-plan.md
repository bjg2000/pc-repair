# PC Repair Business Plan

## Business Info
- **Name:** TBD
- **Location:** Dartmouth, MA (home-based)
- **Structure:** LLC (recommended)
- **Website:** `bjg2000.github.io/<repo-name>` (GitHub Pages — free)

---

## Legal Checklist

### 1. LLC Formation (Massachusetts)
- [ ] File **Certificate of Organization** with MA Secretary of the Commonwealth
  - Online: https://corp.sec.state.ma.us/CorpWeb/Login/Login.aspx
  - Fee: **$500** (one-time filing)
  - Processing: ~5-7 business days
  - Info needed: LLC name, principal office address, resident agent, business purpose
- [ ] Designate a **Resident Agent** (can be yourself with your Dartmouth address)
- [ ] Get **EIN** from IRS (free, online) — needed to open a business bank account
- [ ] **Annual Report** — $500/year, due on anniversary of formation
- [ ] **Operating Agreement** (not required by law but strongly recommended)

### 2. Dartmouth Local Requirements
- [ ] Check **zoning for home occupation** (likely fine for PC repair):
  - Max 600 sq ft used for business
  - Max 1 non-family employee on premises at a time
  - No exterior changes to residential appearance
  - One wooden sign allowed (max 2 sq ft per side, no illumination)
  - Street parking limited — max 2 vehicles regularly parked on street for business
- [ ] File **Business Certificate (DBA)** with Town Clerk if operating under a business name
  - File via Dartmouth View Point Cloud: https://dartmouthma.viewpointcloud.com/
  - Fee: ~$10, valid for 4 years
  - Call Town Clerk at 508-910-1800 with questions
- [ ] Check with **Building/Zoning** department to confirm compliance

### 3. Financial
- [ ] Open dedicated **business bank account** (separate from personal)
- [ ] Set up accounting (Wave is free, QuickBooks if you want more)
- [ ] MA has flat 5% income tax on pass-through LLC profits
- [ ] Track all receipts for deductions (tools, mileage, home office, website costs)

---

## Website (GitHub Pages)

### Tech Stack
- **Hosting:** GitHub Pages (free, `yourname.github.io/pcrepair`)
- **Domain:** Optional — can add a custom domain later (e.g., `dartmouthpcrepair.com`) for ~$12/yr
- **Backend:** None needed to start. For booking/forms, use:

### Booking Options (free tier, works with static sites)
1. **Google Forms** (what you did for the pastry shop) — simplest, embeds as iframe
2. **Calendly** (free tier) — embed link on your site
3. **SchedulingKit** (free) — HTML embed widget on static sites
4. **Self-hosted scheduler via Google Apps Script** (more work but you own it)

### Site Structure (initial)
```
index.html           # Home + services + pricing
booking.html         # Booking/appointment form
contact.html         # Contact info + service area
```

### Google Business Profile
- Free, critical for local visibility
- Set up with your Dartmouth address (service-area business if you don't want clients coming to your house)
- Ask every happy customer for a review

---

## Services & Pricing (Flat Rate)

Pricing is tiered by service method — always cheaper than Geek Squad.

| Service | Drop-off / Remote | In-Home (On-Site) | Geek Squad (for comparison) |
|---------|------------------|-------------------|-----------------------------|
| Diagnostic / Assessment | Free | Free (applied to repair) | $149.99 (baked into repair) |
| Virus / Malware Removal | **$99.99** | **$129.99** | $149.99 |
| OS Tune-Up / Optimization | **$79.99** | **$109.99** | $149.99 |
| OS Reinstall / Upgrade | **$99.99** | **$129.99** | $149.99 |
| PC / Tablet Setup (new device) | **$39.99** | **$69.99** | $99.99 (in-home) |
| Hardware Installation (RAM, SSD, etc.) | **$39.99** + parts | **$69.99** + parts | $39.99 (in-store only) |
| Data Transfer / Backup | **$79.99** | **$109.99** | $99.99 |
| ~~Data Recovery (standard)~~ | N/A | N/A | $249.99 — skip it, liability nightmare |
| Software Setup / Troubleshooting | **$39.99** | **$69.99** | $39.99 (in-store) |
| Thermal Paste Repaste | **$49.99** | **$79.99** | — |
| Pickup & Delivery | $15-25 (within radius) | N/A | N/A |
| Phone / Remote Support | $30-50 (per issue) | N/A | $149.99 (same as in-store) |

*Parts: quote upfront, have customer approve. Offer to order at their expense (Amazon/Newegg next-day). No markup on parts or optional 10-15% — your call.*

### Service Method Options
| Option | How it works | Best for |
|--------|-------------|----------|
| **Drop-off** | They bring PC to your home by appointment | Lower price, you work uninterrupted |
| **Pickup + Delivery** | You grab it and return it | Convenience, elderly/less mobile customers |
| **In-Home (On-Site)** | You go to their place, fix it there | Quick fixes, network/WiFi, showing face = trust |
| **Remote** | TeamViewer/AnyDesk from anywhere | Quick software fixes, no travel needed |

### Why you over Geek Squad
- **$50-150 cheaper** on most services
- **Same-day or next-day** vs 1-3 weeks (Geek Squad ships hardware out)
- **Same person** start to finish — not a different tech every time
- **Direct communication** — call/text you, not a ticket system
- **You come to them** — they don't drag a PC to Best Buy

---

## Operations

### Service Radius
- **Pickup/Delivery / In-Home:** ~10-15 mile radius (Dartmouth, New Bedford, Fall River, Westport, Fairhaven)
- **Drop-off:** Your home — by appointment only, clearly communicated
- **Remote support:** Anywhere (TeamViewer, AnyDesk)

### Logistics — Drop-off / Pickup
- Customer drops off or you pick up
- Give estimate within 24 hrs of diagnosis
- Text/email updates during repair
- Fixed turnaround: 1-3 business days standard, rush available

### Logistics — In-Home (On-Site)
- Schedule a time window (e.g., 2-hr block)
- Bring everything you need — work out of your car
- Basic software/OS work can be done on-site in one visit
- If hardware needs ordering, do a free quick diagnostic visit, order parts, return to install
- Looks more professional — bring an anti-static mat, wear something clean/simple

### Booking Flow
1. Customer visits website or calls
2. Selects service + preferred method (drop-off / pickup / in-home / remote)
3. You confirm via text/email
4. Service performed
5. Payment collected (Venmo, Zelle, Cash, PayPal)
6. Follow-up next week to ensure satisfaction + ask for review

---

## Tools & Inventory (to start)

### Have already
- Screwdriver set
- Compressed air
- Ventoy USB with diagnostic ISOs
- Basic PC knowledge + troubleshooting skills

### Need to buy
- [ ] **Multimeter** ($20-40) — for testing PSU, checking voltages
- [ ] **Anti-static mat** ($15-30)
- [ ] **Thermal paste** ($8-12 per tube, buy as needed)
- [ ] **Cable management ties / small parts organizer**
- [ ] **External HDD/SSD enclosure** ($15-20) — for data recovery/transfer
- [ ] **USB-C / SATA / M.2 adapter** ($15)
- [ ] **Microfiber cloths, isopropyl alcohol** (cleaning)

### In-home / on-site carry kit (pack before every visit)
- Laptop with your diagnostic USB + remote access tools
- Screwdriver kit + multimeter
- Anti-static mat (looks professional)
- Thermal paste + isopropyl alcohol + microfiber cloths
- Zip ties, small parts organizer
- Spare SATA cable, power cable, ethernet cable (just in case)
- Business card / small flyer to leave behind

### Parts inventory (start with nothing, order per-job)
Let customer pay for parts directly. Order from Amazon/Newegg with next-day delivery. Offer to have it shipped to their house or yours.

---

## Marketing (Free/Low-Cost)

- [ ] **Google Business Profile** — set up immediately
- [ ] **Nextdoor** — post in Dartmouth/New Bedford neighborhoods
- [ ] **Facebook Marketplace / local buy-nothing groups**
- [ ] **Craigslist Services section**
- [ ] **Flyers** — library, coffee shops, laundromats, community boards
- [ ] **Word of mouth** — friends, family, coworkers first
- [ ] **Ask every customer for a Google review**

---

## Next Steps (Priority Order)

1. [ ] Pick a business name
2. [ ] Check name availability on MA Corp database
3. [ ] File LLC ($500) + get EIN (free)
4. [ ] Open business bank account
5. [ ] File Business Certificate with Dartmouth ($10)
6. [ ] Set up GitHub Pages site with simple HTML
7. [ ] Set up Google Business Profile
8. [ ] Join Nextdoor + local FB groups
9. [ ] Buy multimeter + anti-static mat
10. [ ] First customer → do great work → ask for review

## Topics for Next Session (unfinished, pick any)

- **Customer flow stuff** — intake forms, service agreements/waivers, payment methods, invoices, how to hand the PC back
- **Branding & vibe** — business name ideas, logo, colors, tone of voice, business cards
- **Policies & protections** — warranty on work, what if something breaks, data privacy, refusal of service
- **Day-to-day ops** — scheduling, communication templates, how to handle busy/slow periods, pricing rush jobs
- **Tax & money stuff** — tracking mileage, deductions, invoicing, quarterly estimated taxes, business bank account
