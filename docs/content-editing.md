# Content Editing Guide

## How Content Works in Craft CMS

Content in Craft is organized into **Entries**. Each entry belongs to a **Section** (like News, Events, or Sponsors) and has specific **Fields** designed for that type of content. This means every content type has exactly the right fields — events have dates and locations, fellows have cohorts and sectors, sponsors have logos and tiers.

## Editing an Existing Entry

1. Go to **Entries** in the sidebar
2. Click on the section you want to edit (e.g., "News & Insights")
3. Click on the entry you want to modify
4. Make your changes in the form fields
5. Click **Save** (top right)
6. Visit the page on the site to see your changes live

## Creating a New Entry

1. Go to **Entries** in the sidebar
2. Click the **+ New Entry** button
3. Select the section type (e.g., "News & Insights" or "Events")
4. Fill in the required fields
5. Click **Save**

The new entry will automatically appear on the site in the appropriate listing page.

## Working with the Page Builder

Several pages (Homepage, About, Invest, Contact) use a **Page Builder** — a flexible set of content blocks you can arrange in any order.

Each block type serves a different purpose:

| Block Type | What It's For |
|------------|---------------|
| Text Block | Rich text content — paragraphs, headings, lists, links |
| Image Block | A single image with optional caption (can be full-width) |
| Two Column | Side-by-side content areas |
| Stats Row | Impact numbers with labels (e.g., "2,500+ Professionals") |
| Pull Quote | A highlighted quote with attribution |
| CTA Banner | A call-to-action section with headline, body, and button |
| Card Grid | A grid of cards with images, titles, and descriptions |

To add a block: click **+ Add a block** at the bottom of the Page Builder field and choose the type.

To reorder blocks: drag and drop them using the handle on the left side.

To remove a block: click the gear icon on the block and select **Delete**.

## Uploading Images and Files

1. When you encounter an **Assets** field (like "Hero Image" or "Featured Image"), click **Add an asset**
2. You can upload a new file or select from existing uploads
3. Supported formats: JPG, PNG, WebP, GIF for images; PDF for documents; MP4 for video
4. Images are automatically optimized for the web

### Image Tips

- **Hero images:** Use high-resolution photos (1920x1080 or larger)
- **Fellow photos:** Square crop preferred
- **Sponsor logos:** Transparent PNG works best
- **Hero video:** MP4 format, H.264 codec, ideally under 10MB, 10-30 seconds

## Managing Sponsors

Sponsors are their own section in Craft. To add a new sponsor:

1. Go to **Entries → Sponsors**
2. Click **+ New Entry**
3. Fill in the sponsor name, upload their logo, add their website URL, and select their tier (Diamond, Gold, Silver, Bronze)
4. Save

The sponsor will automatically appear on the Invest page and Homepage sponsor sections.

## Managing Events

Events have rich fields for dates, locations, and registration:

1. Go to **Entries → Events**
2. Click **+ New Entry** or edit an existing event
3. Key fields:
   - **Event Date / End Date** — When the event starts and ends
   - **Location** — Venue name and city
   - **Event Type** — Summit, Seminar, Networking, Workshop, or Webinar
   - **Registration URL** — Link to external registration (e.g., Neon)
   - **Description** — Full event details
   - **Flagship Event** — Toggle this on to highlight the event prominently on the events page
4. Save

Events automatically appear on the Events listing page and calendar view, sorted by date.

### After an Event

You can add recap content to past events:

- **Recap Text** — A post-event write-up
- **Recap Photos** — Upload photos from the event

## Managing Fellows

1. Go to **Entries → Fellows**
2. Each fellow has: photo, name, company, cohort, program, sectors, location, social links, and bio
3. Toggle **Featured** to include a fellow in the homepage carousel
4. Fellows automatically appear in the Alumni Directory with filtering by cohort and sector

## Managing News & Insights

1. Go to **Entries → News & Insights**
2. Each article has: featured image, excerpt (for cards), body content, and optional external URL
3. If **External URL** is set, the card on the News page will link externally (useful for press coverage)
4. Tags categorize articles as Press, Announcement, or Insight

## Tips

- **Save often** — Craft autosaves drafts, but clicking Save publishes your changes
- **Preview** — Use the Preview button to see how changes look before saving
- **Undo** — If you make a mistake, Craft keeps revision history. Click the revision menu (top of the entry) to restore a previous version
