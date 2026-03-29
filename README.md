# The Builder Coalition — Craft CMS Proof of Concept

## What This Is

A proof of concept of what TBC's website could look like on a professional CMS platform — Craft CMS. This is running on a private development server. It's not live, not public, and doesn't affect your current site in any way.

This repository contains documentation and guides for exploring the sandbox environment. The source code, templates, and design assets are maintained separately and are not included here.

---

## Access the Sandbox

**Site URL:** https://sandbox.saicloud.org

You'll be prompted to log in with your email when you first visit (this is a private preview gate — only TBC team members can access it).

**Admin Panel:** https://sandbox.saicloud.org/admin

Log in with the credentials provided to you separately. From here you can create, edit, and manage all site content.

---

## What's Built

**12 fully functional pages:**

- **Homepage** — Hero with video/image, mission statement, impact stats, upcoming events, sponsor logos, CTAs
- **About** — TBC's five platform pillars, program map, narrative sections
- **Our Impact** — Animated impact metrics, key accomplishments
- **Our Team** — Staff, consultants, and board members with filtering
- **Events** — Full event listing with calendar view, category filters, event detail pages, and .ics calendar subscription
- **News & Insights** — Press coverage and announcements with category filtering
- **Contact** — Contact form, email, phone, address, LinkedIn
- **Invest** — Partnership pitch, impact stats, sponsorship tiers, sponsor logos, CTA
- **TBC Institute** — Fellowship programs overview, featured fellows, testimonials
- **Alumni Directory** — Searchable fellow directory with cohort and sector filtering
- **Fellow Profiles** — Individual fellow pages with bio, social links, related fellows
- **Fellowship Programs** — Program detail pages with status badges and application CTAs

Remaining pages are stubbed with branded "Coming Soon" placeholders (Innovation Center, Directory, Jobs Board, etc.). These would be built out if the project moves forward.

---

## Documentation

| Guide | Description |
|-------|-------------|
| [Getting Started](docs/getting-started.md) | How to log in, navigate the admin panel, and what you can do |
| [Content Editing](docs/content-editing.md) | How to create and edit entries, upload images, manage content |
| [Content Model](docs/content-model.md) | What sections exist, what fields they have, how content is organized |
| [Site Map](docs/site-map.md) | Page hierarchy, navigation structure, and URLs |
| [FAQ](docs/faq.md) | Common questions and what to do if something goes wrong |

---

## What Makes This Different From Squarespace

| | Squarespace | Craft CMS |
|---|---|---|
| **Content structure** | Generic blocks, one-size-fits-all | Custom fields for every content type (events have dates/locations, fellows have cohorts/sectors, sponsors have tiers/logos) |
| **Editing experience** | Edit the page visually, limited structure | Edit structured data in clean forms, site renders it beautifully |
| **Events** | Basic, no calendar view or .ics | Full calendar, category filters, .ics subscription, detail pages |
| **Fellow directory** | Would need a workaround | Built-in: searchable, filterable, linked to programs |
| **Sponsor management** | Manual image placement per page | Add once, appears everywhere automatically |
| **Performance** | Squarespace controls it | We control it — currently loads in under 2 seconds |
| **Ownership** | Squarespace owns the platform | TBC owns everything — code, content, hosting accounts |

---

## Questions or Issues?

Contact Sai — boddupops@gmail.com
