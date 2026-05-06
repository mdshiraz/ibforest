# IB Forest — Family Tree

A web-based family tree hosting application with a vintage/sepia aesthetic. Browse, manage, and visualize family genealogy data.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Main family tree viewer — browse members, view relationships |
| `index.mcp.html` | MCP-enabled variant of the main viewer |
| `admin.html` | Admin panel — manage family members and data |
| `analytics.html` | Visitor analytics dashboard |
| `akt.html` | AKT utility page |
| `tribe_data.js` | Core tribe/family data file |

## Project Structure

```
ibforest/
├── index.html          # Main family tree viewer
├── index.mcp.html      # MCP variant
├── admin.html          # Admin panel
├── analytics.html      # Analytics dashboard
├── akt.html            # AKT page
├── tribe_data.js       # Family data
└── legacy/             # Archived older versions
    ├── index/          # Previous index versions
    ├── admin/          # Previous admin versions
    ├── analytics/      # Previous analytics versions
    └── tribe_data/     # Previous data file versions
```

## Tech Stack

- Vanilla HTML/CSS/JavaScript (no build step)
- [Supabase](https://supabase.com) for backend data storage
- Google Fonts — Playfair Display, Source Sans 3, JetBrains Mono
