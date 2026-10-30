# Pulse Dashboard – Style Guide

## Colours (light theme)
| Token | Hex | Used for |
|---|---|---|
| `--brand` | `#6d5dfc` | Primary buttons, links, active bar |
| `--brand-2` | `#9a8cff` | Bar-chart gradient top, active nav edge |
| `--teal` | `#16c4a8` | Orders, "Paid" status, positive deltas |
| `--amber` | `#ffb020` | Customers, "Pending" status |
| `--rose` | `#ff5c7c` | Badges, "Refunded", negative deltas |
| `--ink` | `#1b1d2e` | Main text |
| `--muted` | `#7b7f99` | Secondary text, labels |
| `--line` | `#e8eaf3` | Borders, table rules, chart grid |
| `--bg` | `#f4f5fb` | Page background |
| `--card` | `#ffffff` | Cards |
| Sidebar | `#2a2150` → `#1b1536` | Vertical gradient (top → bottom) |

Tinted chip backgrounds: violet `#ece9ff`, teal `#d9f7f1`, amber `#fff1d6`, rose `#ffe3e9`.
Status text: ok `#0c9a83`, pending `#b87400`, refunded `#e0405f`.

## Colours (dark theme)
`--bg #0f1020` · `--card #171932` · `--ink #eceefb` · `--muted #9296b5` · `--line #262949`

## Typography
- Font: **Inter** (fallback: system-ui, Segoe UI, Roboto, sans-serif) – https://fonts.google.com/specimen/Inter
- Base 15px / 1.5 · Page title 26px bold (letter-spacing −0.02em) · Card title 17px bold
- KPI value 30px extra-bold (−0.03em) · Table headers 12px uppercase, +0.06em tracking

## Spacing, shape, depth
- Page padding 28px 32px · gap between cards 20–24px · card padding 20px
- Card radius **16px** · chips/buttons 10–12px · pills fully rounded (99px)
- Card shadow: `0 1px 2px rgba(27,29,46,.04), 0 8px 24px rgba(27,29,46,.06)`
- Layout: sidebar **240px** fixed + fluid content (CSS Grid)

## Breakpoints
- ≤ 1000px: two-column rows become one column
- ≤ 760px: sidebar becomes a horizontal bar, content padding shrinks
