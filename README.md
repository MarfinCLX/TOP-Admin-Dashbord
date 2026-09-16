Admin Dashboard

A responsive admin dashboard layout built as part of The Odin Project's Intermediate HTML & CSS Grid section — recreating a typical dashboard UI (sidebar, header, project cards, announcements, and trending panels) using CSS Grid for the page structure and Flexbox for the content within each section.

🎯 Goals

- Practice CSS Grid for real page layout, not just isolated exercises
- Combine Grid (outer page structure) with Flexbox (inner content alignment) — Grid for the big layout regions, Flex for arranging items within them
- Work with `grid-column` / `grid-row` line-based placement instead of named `grid-template-areas`
- Nest an independent Grid inside a Grid area (the project cards grid lives inside the main content area)
- Practice auto-placement (`repeat(auto-fit, ...)`) for a card grid that doesn't require manually positioning every item

✨ Layout Overview

- Sidebar — spans the full height of the page, fixed-width column
- Header — search bar, notifications, user profile
- Main content — "Your Projects" card grid (auto-placed, no manual `grid-column`/`grid-row` per card)
- Right column — Announcements and Trending panels

🛠 Tech Stack

- HTML5 — semantic structure
- CSS3 — CSS Grid (page layout), Flexbox (in-component alignment), custom properties

📁 Project Structure

```
admin-dashboard/
├── index.html      Page markup
├── style.css         Grid layout, Flexbox components, styling
└── README.md          Project documentation
```

Status

Complete.

---

Practice project — part of The Odin Project's Intermediate HTML & CSS curriculum.

Developed by MarfinCLX
