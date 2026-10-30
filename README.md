# Pulse Dashboard – HTML & CSS Practice Kit

Rebuild the dashboard in `design-reference/` using only HTML and CSS.

## What's inside
| Folder / file | What it is |
|---|---|
| `design-reference/` | The target design (light + dark, 1440px wide). Match this. |
| `style-guide.md` | Every colour, font size, spacing and radius you need |
| `assets/palette.png` | Colour swatches with hex codes |
| `assets/logo/` | Logo (64/128/512px) and wordmarks (dark and white) |
| `assets/icons/nav/` | 6 sidebar icons, white and muted versions |
| `assets/icons/kpi/` | 4 KPI card icons (violet, teal, amber, rose) |
| `assets/icons/topbar/` | Search and bell icons |
| `assets/avatars/` | 6 initials avatars (RY, AB, KJ, FS, OD, LC) |
| `assets/charts/` | Donut chart and bar chart (light/dark) as PNGs |
| `assets/backgrounds/` | Sidebar gradient image |
| `starter/` | Empty `index.html` and `style.css` with the colours pre-set |
| `solution/` | Finished version. **Don't peek until you've tried!** |

## Challenge levels
1. **Easy:** build the layout with images – sidebar, KPI cards, and the table. Use the PNG icons, avatars and charts.
2. **Medium:** do the charts in CSS instead of images: bars with flexbox and `height`, the donut with `conic-gradient`, the progress bar with `width`.
3. **Hard:** add the dark theme with `@media (prefers-color-scheme: dark)` by changing only the CSS variables, plus responsive breakpoints.
4. **Bonus:** hover effects, a collapsible sidebar, and the Week/Month/Year buttons with a little JavaScript.

## Tips
- Start with the page layout: `display:grid; grid-template-columns:240px 1fr`.
- Define colours as CSS variables first (see `starter/style.css`).
- KPI row: `grid-template-columns: repeat(auto-fit, minmax(210px, 1fr))`.

## Dashboard project
- this project is a responsive admin dashboard built with HTML and css. it includes dashboard cards, sales information, revenue charts, customers details, and recent activities.

## screenshot 
- ![dashboard screenshot](images/Screenshot%202026-10-30%20195105.png)
- ![dashboard screenshot](images/Screenshot%202026-10-30%20195243.png)
