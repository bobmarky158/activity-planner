# Daylight activity planner

A responsive activity planner with weekly and list views, editable activities, categories, completion tracking, browser saving, backup import/export, calendar export, and printing.

## Website

https://bobmarky158.github.io/activity-planner/

## Hosting

The site is a self-contained `index.html`. GitHub Pages serves the `main` branch from the repository root. No build step or dependencies are required.

## Data storage

Each visitor's plan is stored in their own browser. Plans are not sent to GitHub, shared with other visitors, or synchronized between devices. Export a JSON backup before clearing browser data. Importing a backup replaces the current plan after confirmation.

Calendar exports include all weeks. Timed activities use the destination calendar's local time zone; activities without a start time become all-day events. Calendar export does not set up synchronization.

## Embed

```html
<iframe src="https://bobmarky158.github.io/activity-planner/" title="Activity planner" style="width:100%;height:1000px;border:0;border-radius:16px;" loading="lazy"></iframe>
```

Browser settings may limit storage in cross-site embeds. A direct link to the planner provides the most dependable storage.
