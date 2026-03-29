# Content Model Overview

This document describes how content is organized in the CMS. Understanding this structure will help you find and manage content effectively.

## Sections at a Glance

| Section | Type | What It Contains |
|---------|------|-----------------|
| **Home** | Single page | Homepage hero, mission, impact stats, events, sponsors, CTAs |
| **About** | Channel | About pages — Our Work, Our Impact, Our Team |
| **Invest** | Single page | Partnership pitch, sponsorship tiers, sponsor logos |
| **Contact** | Structure | Contact form, address, phone, email |
| **Events** | Channel | Event listings with dates, locations, registration links |
| **News & Insights** | Channel | Press coverage, announcements, articles |
| **Fellows** | Channel | Fellow profiles for the alumni directory |
| **Fellowship Programs** | Channel | Program descriptions with status and application links |
| **Sponsors** | Channel | Sponsor entries with logos and tier levels |

## Content Types Explained

### Single Pages

These are one-off pages with unique layouts. You edit them directly — there's only one entry per section.

- **Home** — The homepage. Has hero fields at the top and a page builder for content sections below.
- **Invest** — The fundraising/sponsorship page.

### Channels

These are collections of similar entries. You can add as many as you want.

- **Events** — Each event has its own date, location, type, registration URL, and description. Events auto-sort by date on the listing page and calendar view.
- **News & Insights** — Articles and press links. Can be tagged as Press, Announcement, or Insight.
- **Fellows** — Individual profiles. Each fellow has a photo, bio, cohort, program, sectors, and social links.
- **Sponsors** — Each sponsor has a name, logo, website, and tier (Diamond/Gold/Silver/Bronze). Adding a sponsor here automatically shows them on the relevant pages.

## Key Fields by Section

### Homepage

| Field | What It Controls |
|-------|-----------------|
| Hero Headline | Large heading over the hero image/video |
| Hero Subhead | Supporting text below the headline |
| Hero Image | Background photo (fallback when no video) |
| Hero Video | Background video (MP4, autoplays muted) |
| Hero CTA buttons | Up to 2 call-to-action buttons on the hero |
| Page Builder | Content sections below the hero (mission, stats, sponsors, etc.) |

### Events

| Field | What It Controls |
|-------|-----------------|
| Event Date / End Date | When the event occurs |
| Location | Venue name and city |
| Event Type | Summit, Seminar, Networking, Workshop, or Webinar |
| Registration URL | Link to sign up (e.g., Neon registration) |
| Description | Full event details |
| Flagship Event | Toggle to feature prominently on the events page |
| Recap Text / Photos | Post-event content (added after the event) |

### Fellows

| Field | What It Controls |
|-------|-----------------|
| Fellow Photo | Headshot (square crop preferred) |
| Name / Company | Identifying info shown on cards and profiles |
| Cohort | Which cohort they belong to (e.g., Core 2024, AHDF 2025) |
| Fellowship Program | Core Fellowship, AHDF, or Investment Analysis |
| Sector | Areas of focus (Affordable Housing, Commercial, etc.) |
| City / State | Location |
| LinkedIn / Website | Social links |
| Bio | Full biography |
| Featured | Toggle to show on the homepage carousel |

### News & Insights

| Field | What It Controls |
|-------|-----------------|
| Featured Image | Photo shown on the article card |
| Excerpt | Short description for listing pages (200 characters) |
| Body Content | Full article text |
| External URL | If set, the card links externally (for press coverage) |
| Tags | Press, Announcement, or Insight |

### Sponsors

| Field | What It Controls |
|-------|-----------------|
| Sponsor Name | Organization name |
| Logo | Sponsor's logo image |
| Website URL | Link to sponsor's site |
| Tier | Diamond, Gold, Silver, or Bronze |

## How Things Connect

- **Homepage events** auto-populate from the 3 nearest upcoming events. This can be manually overridden.
- **Sponsors** added as entries automatically appear on the Invest page and Homepage sponsor sections.
- **Featured fellows** (with the Featured toggle on) appear in the homepage fellow carousel.
- **News articles** with an External URL set will link out to the original source instead of an internal page.
