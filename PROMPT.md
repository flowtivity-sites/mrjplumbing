# MRJ Plumbing - Website Rebuild

## Overview
This is a website rebuild for **MRJ Plumbing**, a trades business.

## Quick Start
```bash
npx create-next-app@latest . --typescript --tailwind --app --src-dir --no-eslint
npm run dev
```

## Design Direction
- **Aesthetic:** Industrial Authority
- **Display Font:** Bebas Neue
- **Body Font:** Work Sans
- **Primary Color:** #1a365d
- **Accent Color:** #ff8c42
- **Effects:** geometric shapes, grain texture, bold shadows, decorative lines

## Design Variations Available
This site has 4 unique design variations to choose from. The recommended variation is applied below, but you can switch by updating `selectedVariation` in prd.json.

### Industrial Authority (variation-1) - RECOMMENDED
- **Rationale:** This design reflects MRJ Plumbing's comprehensive service range across major Australian regions with bold, industrial aesthetics. The navy and orange palette conveys trust and urgency - perfect for emergency plumbing situations while maintaining professional credibility for insurance and real estate work.
- **Palette:** Primary #1a365d, Accent #ff8c42
- **Fonts:** Bebas Neue / Work Sans
- **Mood:** authoritative, industrial, reliable

### Coastal Professional (variation-2)
- **Rationale:** Drawing inspiration from MRJ's Gold Coast location, this design uses teal and charcoal to reflect both water expertise and professional reliability. The clean layout emphasizes their specialized CCTV and leak detection services while maintaining approachability for residential clients.
- **Palette:** Primary #0d9488, Accent #fbbf24
- **Fonts:** Space Grotesk / DM Sans
- **Mood:** flowing, professional, approachable

### Trade Specialist (variation-3)
- **Rationale:** This variation emphasizes MRJ's technical expertise in specialized services like CCTV inspection and water intrusion investigation. The bold typography and high-contrast design communicates confidence and precision - essential for insurance reporting and pre-purchase inspections.
- **Palette:** Primary #1f2937, Accent #10b981
- **Fonts:** Archivo Black / Source Sans Pro
- **Mood:** technical, precise, confident

### Regional Reliability (variation-4)
- **Rationale:** Designed to emphasize MRJ's extensive coverage across Gold Coast, Brisbane, and Northern NSW, this warm and trustworthy design appeals to both residential and commercial clients. The earthy palette suggests reliability and established expertise in the region.
- **Palette:** Primary #7c3aed, Accent #f59e0b
- **Fonts:** Oswald / Inter
- **Mood:** established, regional, comprehensive


## Business Information
- **Name:** MRJ Plumbing
- **Phone:** 0416 741 718
- **Email:** nik@mrjplumbing.com.au


- **Tagline:** All Plumbing Services Across the Gold Coast, Brisbane, and Northern NSW

## Services
### General Plumbing
Professional general plumbing services

### Leak Detection
Professional leak detection services

### CCTV / Water Intrusion Investigation
Professional CCTV / water intrusion investigation services

### Plumbing Services
Professional plumbing services

### CCTV / Water Intrusion
Professional CCTV and water intrusion services

### Pre Purchase Home, Plumbing Inspection Report
Provides a plumbing system inspection before signing a house contract, including CCTV inspection of sewer and stormwater systems, water mains pressure testing, and review of leaking pipes.

### Insurance Reporting for Water Intrusions
Experienced in insurance reporting relating to plumbing and water intrusions, using Thermal Imaging Camera technology to provide supporting images and video.

### Real Estate Agents
Provides plumbing solutions to real estate property managers with fast, efficient, and honest reporting.

### Stormwater Drainage
Addresses stormwater drainage issues, including agricultural pipe replacement, driveway grate installation, and downpipe redirection.

### Blocked & Broken Drain Diagnosis
Uses CCTV technology to identify pipe breaks or tree roots causing blockages, and offers drain unblocking and cleaning services.

### Burst Pipe Repair
Professional burst pipe repair services

### Burst Pipes
MRJ Plumbers use acoustic technology to locate underground water leaks and repair or redirect the pipework.

### Mains Water Leaks
MRJ Plumbing suggests checking if water is passing through your water meter if you find water surfacing on your property or received a notice from the council regarding excess usage.

### Roof Plumbing Leaks
Nik can identify cracked tiles, leaking gutters, roof flashing issues and discuss solutions to stop water from entering your house.

### Apartment Patio Leaks
MRJ Plumbing can identify leaks from an apartment above using infrared camera technology, then provide a detailed report with supporting images.

### House Water Intrusion
MRJ Plumbing use Thermal Imaging Cameras to identify leaks in your ceiling, walls and anywhere you can't access. MRJ Plumbing can locate the problem and provide a solution.

### Bathroom Renovations
Bathroom renovation services including underground pipework redirection, installing showers, basins, and tapware.

### Kitchen Renovations
Kitchen renovation services, working with existing pipework or discussing solutions for plumbing redirection.

### Laundry Renovations
Laundry renovation services including removal of old laundry fixtures and replacement with new.

### Toilet Repair and Replacement
Toilet repair and replacement services to address leaking or dripping toilets.

### Leaking Tap and Shower Head Repairs
Repair and replacement services for leaking taps and shower heads.

### Dishwasher Plumbing and Installation
Dishwasher plumbing and installation services including reviewing water supply, redirecting pipework, fixing isolation taps, and installing new dishwashers.

### Fridge Water Points and Plumbing
Plumbing services to redirect pipework for fridge water points.

### Hotwater Systems
Hot water system services to address expiry dates, leaks, and corrosion.

### Rainwater Tank Installation
Rainwater tank installation services, connecting gutters to tanks and ensuring proper storm water runoff.

### CCTV/WATER INTRUSION
Professional CCTV/WATER INTRUSION services

## Available Images
**IMPORTANT:** Use these downloaded images from the original website. Do NOT use placeholder images.

No images downloaded - use placeholder images sparingly

## Content Files
- `content/pages.json` - Scraped page content
- `content/services.json` - Service offerings
- `content/about.json` - About/team information
- `content/metadata.json` - Business contact details
- `assets/images/` - Downloaded images from original website

## PRD Stories
Complete each story in `prd.json` in order. Mark `"passes": true` when done.

1. **Project setup: Next.js + Tailwind, Cloudflare config**
2. **Homepage: hero with images, services grid, trust signals, CTA**
3. **Services page with service images**
4. **About page with team/business images**
5. **Contact page: form, map, details**
6. **Design system: Apply vertical aesthetic**
7. **Motion & polish**
8. **AEO: LocalBusiness schema, meta tags, FAQ**
9. **Mobile responsive**
10. **Image optimization with next/image**
11. **Deploy to Cloudflare Pages**

## Deployment
```bash
npm run build
npx wrangler pages deploy ./out --project-name=mrjplumbing
```

Preview URL: `https://mrjplumbing.sites.flowtivity.com.au`

---
Generated by Website Factory
