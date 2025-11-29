# Studio Intangible - Pricing Calculator

Interactive pricing calculator for Studio Intangible's AI video content services.

## Overview

Two main offerings:
- **Credit Packs** - One-time purchases for project-based work
- **Monthly Retainers** - Ongoing subscriptions with bonus credits and included support

## Features

- Interactive tier selection with dynamic pricing
- Credit calculator to estimate needs
- Annual/monthly billing toggle with savings display
- Service level selection (Files-Only Delivery vs Full Service Implementation)
- Responsive design for all devices
- Direct integration with Stripe payment links and calendar booking

## Deployment

This is a standalone HTML file with all CSS and JavaScript inline. No build process required.

### Setup Steps

1. **GitHub** ✅
   - Repository created and code pushed

2. **Netlify**
   - Connect to this GitHub repo
   - Auto-deploys on push to main branch
   - Optional: Set up custom domain (e.g., `pricing.studio-intangible.com`)

3. **Stripe Payment Links**
   - Create 10 payment links (see documentation)
   - Add links to `STRIPE_LINKS` object in code

4. **Calendar Booking**
   - Set up Cal.com or Calendly page
   - Add link to `CALENDAR_LINK` constant in code

5. **Framer Integration**
   - Add button/link to Netlify URL
   - Opens pricing calculator in new tab or same window

## Product Structure

### Credit Packs
- **Starter**: €1,750 (10 credits, 3 months)
- **Growth**: €4,500 (25 credits with 2 bonus, 3 months)
- **Scale**: €6,750 (50 credits with 5 bonus, 3 months)

### Monthly Retainers
- **Starter**: €2,500/mo or €25,000/year (10 credits/mo or 120/year)
- **Growth**: €5,500/mo or €55,000/year (25 credits/mo or 300/year)
- **Scale**: €8,250/mo or €82,500/year (50 credits/mo or 600/year)

All retainers include:
- Launch Support (€1,250 value) - free
- Quarterly review calls
- Performance analytics integration

### Service Levels (Retainers Only)
- **Files-Only Delivery**: Included - Files via Frame.io, basic support
- **Full Service Implementation**: +€1,500/mo - Complete hands-off experience

## Credit Costs

| Asset Type | Credits | Description |
|------------|---------|-------------|
| 360° Packshot | 1 | Full rotation spin |
| Subtle Animation | 1 | Gentle movement on hover |
| Colour Transform | 2 | Morph between 2 colours/materials |
| Interactive Hover | 3 | Customer-controlled interaction |

## File Structure

```
studio-intangible-pricing/
├── index.html          # Main pricing calculator (all-in-one file)
├── README.md           # This file
└── .gitignore
```

## Technical Notes

- Single HTML file with inline CSS and JavaScript
- No external dependencies (uses system fonts)
- Fully responsive with breakpoints at 900px, 800px, 600px, 500px, 400px
- ES6 JavaScript with state management
- Mobile-optimized with touch-friendly controls

## Next Steps

- [ ] Create Stripe payment links (10 total)
- [ ] Set up calendar booking page
- [ ] Add payment/calendar links to code
- [ ] Deploy to Netlify
- [ ] Test all payment flows
- [ ] Link from Framer site

---

Built for Studio Intangible
