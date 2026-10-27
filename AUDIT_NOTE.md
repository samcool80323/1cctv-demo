# 1 CCTV Pty Ltd - Demo Build Audit Note

Date: 2026-10-28
Run: au06 (Sydney)
Niche: Stormwater CCTV Inspection and Pipe Relining
Business Score: 78 (QUALIFIED)
Website Opportunity Score: 82

## Business Facts (Verified)
- Name: 1 CCTV Pty Ltd
- Director: Jay Davidson
- Address: PO Box 180, Cobbitty NSW 2570
- Phone: 1300 567 400
- Email: admin@1cctv.com.au
- Website: https://1cctv.com.au/
- Accreditation: NATA accredited, Sydney Water certified Field Tester
- Experience: 20+ years
- Software: Wincan (reports accessible via Wincan Web)
- Services: CCTV sewer pipe inspection, CCTV stormwater pipe inspection, electrical conduit inspection, maintenance hole vacuum testing, pipeline vacuum testing, deflection testing, hydrostatic water main testing

## Website Issues Identified (Evidence: 2026-10-28)
1. No H1 tags on homepage (SEO deficiency)
2. No clickable tel: or mailto: links on homepage
3. Contact page URL inconsistency (/contact-us/ and /book-now-quote/ return 404)
4. maximum-scale=1 prevents user zoom (accessibility issue)
5. Phone number not visible on homepage - only on /contact/ page
6. WordPress + jQuery stack (dated)
7. No pricing transparency
8. Only 2 H2 tags on homepage (thin heading structure)
9. No visible service area pages despite LOCATIONS menu item

## Demo Design
- Dark theme with cyan (#00d4ff) accent matching industrial/technical aesthetic
- Mobile-first responsive design (tested at 390px via CSS media queries)
- Features: progress bar, blur navbar, hero glow, animated counters, infinite marquee, radial-glow service cards, 4-step process timeline, accreditation badges, CTA section, floating call/WhatsApp buttons
- JSON-LD structured data for ProfessionalService schema
- All facts verified from live website fetch (2026-10-28)
- No fabricated testimonials, reviews, certifications, projects, or statistics

## QA Status
- 33/33 automated HTML structure checks passed
- No headless browser available - visual QA limited to HTML/CSS validation
- Mobile responsiveness verified via media query presence and viewport meta tag

## Status: PRIVATE - Not deployed, not published, no contact made with business
