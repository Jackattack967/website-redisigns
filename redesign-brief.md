# Website redesign concepts: handoff brief

Build three single-page homepage concepts, one per business below, as self-contained HTML files (`kingsway-computers.html`, `budget-save-painters.html`, `marvs-drycleaners.html`). These are pitch mockups to show the owners, not live sites.

## Ground rules for all three
- Use only the facts listed here. Don't invent prices, warranties, policies, awards or reviews.
- Testimonials: leave clearly marked placeholder slots ("Paste a real Google review here"). Don't write fake reviews.
- Add a slim ribbon at the top of each page: "Concept redesign for [Business]. Not the official website."
- Forms must not submit anywhere. On submit, show a message saying this is a concept and that the live version would send to the business's email.
- Responsive down to ~360px wide, visible keyboard focus, respect `prefers-reduced-motion`.
- Each business gets its own distinct visual identity. Avoid generic templates (cream + serif + terracotta, SaaS card grids, ALL-CAPS eyebrow labels, "→" on every button).
- Spend boldness on one memorable element per page; keep the rest quiet.
- No stock photos available. Use CSS/SVG illustration or typography instead.

---

## 1. Kingsway Computers Ltd.
**Why they need it:** current site (kingswaycomputer.com) shows "Copyright 2012-2023", leads with a fax number, has a broken "Mail: Mail:" line with no email, and almost no content. Yet the business is strong: 4.9 stars, ~194 Google reviews.

**Facts**
- Address: 18-4429 Kingsway, Burnaby, BC V5H 2A1 (near Metrotown)
- Phone: 604-222-1000
- Email: derek@kingswaycomputer.com (owner/manager is Derek)
- In business since 2007
- Hours (per Google, confirm with owner): Mon closed · Tue–Fri 10:30am–5:30pm · Sat 9:30am–4:00pm · Sun closed
- Services: start-up issues, slow performance, system crashes, motherboard replacement, memory upgrades, SSD/drive replacement, software install, Windows upgrades/OS reinstall, laptop screen and keyboard repair, wireless and printer problems, network setup, data backup, virus/spyware/adware cleanup, custom-built PCs, on-site service, repairs on all makes including older models
- Their own positioning: name-brand, industry-standard components; every machine rigorously tested before it goes out; friendly, knowledgeable people

**Design direction:** "repair bench." Cool, trustworthy palette (ink navy #14213D, steel #4E5D70, mist #E9EEF3, white, amber status-light accent #F0A030). Type: Bricolage Grotesque for display, Atkinson Hyperlegible for body (readable for an older clientele).
**Memorable element:** hero has a "What's your computer doing?" picker. Tapping a symptom (won't turn on / running slow / pop-ups or virus / broken screen or keyboard / need my files back / want a new PC) swaps in a short plain-language answer plus a call button.
**Sections:** header with tap-to-call phone → hero + symptom picker → visit the shop (address, hours with today highlighted, Google Maps directions link) → services list → review placeholders with "4.9 on Google" → footer.

---

## 2. Budget & Save Painters
**Why they need it:** the site looks modern, but the quote form on the Burnaby page shows "Google reCaptcha: Invalid site key", so quote requests are likely failing. Copy is also repetitive (duplicated menus, the same "trusted painters" message repeated). The site lists a Vancouver address (1200 W 10th Ave) while directories list Burnaby (2276 Kensington Ave); ask the owner which to show.

**Facts**
- Phone: 778-737-8989
- Email: budgetpaintersonline@gmail.com
- Since 2003
- 4.9 stars, 178 Google reviews (per their site)
- 13+ HomeStars awards; Three Best Rated 2022–2026; BBB listed
- Hours: Mon–Fri 6am–10pm · Sat–Sun 6am–7:30pm
- Services: interior, exterior, residential, commercial, strata, deck & fence, power washing, colour consultation, flooring, renovation
- Free estimates; warranty; 100% satisfaction guarantee
- Promo (from a directory listing, confirm it's current): 35% off residential & commercial projects
- Service area: Vancouver, Burnaby, Port Moody, Richmond, North Vancouver, West Vancouver, plus Kitsilano, Dunbar, Fairview, Mount Pleasant, Point Grey, Shaughnessy, Kerrisdale, UBC

**Design direction:** painter's-tape and paint-swatch world. Crisp white walls, deep spruce #1F3A33 for text blocks, painter's-tape blue #3A7BD5 accent, swatch-chip colours for project types. Type: Archivo, using its width axis (wide for headlines, normal for body).
**Memorable element:** one orchestrated page-load moment: a roller stripe of fresh colour sweeps across the hero wall, revealing the headline.
**Sections:** hero with a short quote form front and centre (project-type swatch chips: interior / exterior / commercial / deck & fence / other; name, phone, neighbourhood, short note). This is the pitch point: "your form works now." Then services, why-us proof strip (since 2003, 4.9 rating, awards), areas served, review placeholders, footer with hours.

---

## 3. Marv's One Hour Drycleaners
**Why they need it:** no website at all, only a Facebook page (facebook.com/MarvsDrycleaners). Long-time customers (one review mentions three decades).

**Facts**
- Address: 4786 Imperial St, Burnaby, BC V5J 1C2
- Phone: 604-433-6112
- Hours (per Google, confirm): Mon 10:30am–3:30pm · Tue–Sat 9am–5pm · Sun closed
- Services: dry cleaning, one-day cleaning option, wedding gowns, duvets and comforters, delicate and beaded garments, stain treatment, alterations and tailoring (hemming, sleeve shortening, repairs), laundry wash & fold, ironing, uniforms
- Promo: $5 off dry cleaning dresses
- Price list (from a directory listing, confirm prices are current):
  - Men's shirts (laundered & pressed) $2.50
  - Pants $5.50
  - Blouse, skirt, rayon shirt & tie $6.99
  - Blazers & sweaters $7.99
  - Dresses $11.99
  - 2-piece suit (men's or women's) $12.99
  - 3/4 winter coat, raincoat, ski jacket $16.99
  - Down duvet single/double $25.99 · queen $30.99 · king $35.99
  - Wedding dresses $69.99
- Don't promise one-hour turnaround; it's the business name. Say "one-day service available."

**Design direction:** heritage dry-cleaner signage meets claim tickets. Navy #1D2B53, ticket red #D6404F, claim-ticket yellow #FFF3C4, hanger-wire grey #8A8F98, white. Type: Yellowtail script for the "Marv's" logotype (old storefront sign feel), Chivo for everything else.
**Memorable element:** the price list is the centrepiece, styled as perforated claim tickets or a hanging tag board you can scan quickly.
**Sections:** hero ("Marv's" sign logotype, one-day service, call + directions) → price list → specialties (wedding gowns, delicates, alterations) → the $5 dress promo → hours and location → review placeholders → footer with Facebook link.

---

## When done
Screenshot each page at desktop (1280px) and mobile (390px) widths, fix any layout issues, and double-check every fact on the page against this brief.
