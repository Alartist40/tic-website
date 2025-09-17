# 📄 TIC Website – Project Requirements Document (PRD)
**Version:** 1.2  
**Date:** 2025-09-17  
**Author:** Codex (AI Mentor) + User Collaboration  

## 1. Project Name & Goal
Build a **modern, brochure-style website** for **Tokyo International Seventh-day Adventist Church (TIC)** that:
- Showcases church identity, values, leadership, ministries, and service times
- Visually celebrates the **Sabbath** via a **7-column Creation Grid**
- Provides **live** Google Calendar & Maps integration
- Remains **static-file based** for easy hand-off to church IT

## 2. Core Features (MVP v1.2)
| Feature | Status | Notes |
|---------|--------|-------|
| **7-Column Creation Grid** | ✅ | 6/7 content, 1/7 Sabbath column (sticky, logo-centred) |
| **Sticky Nav Bar** | ✅ | Hover glow + click scale, no overlap with Sabbath stripe |
| **Hover Language** | ✅ | Subtle lift + gold border on cards & buttons |
| **Smooth Scroll Offset** | ✅ | Auto-lands below sticky nav |
| **About Section** | ✅ | Pastor cards, verse box, round portraits, mission/vision list |
| **Ministries** | ✅ | Expandable sub-cards (Pathfinders, Adventurers, Children's) |
| **Sermons** | ✅ | **Page link** to YouTube channel (not embed) |
| **Events** | ✅ | Live Google Calendar iframe |
| **Visit Us** | ✅ | Service table + correct Maps pin + directions |
| **Responsive** | ✅ | Sabbath stripe hides ≤900 px, nav stacks, cards reflow |
| **Fonts & Palette** | ✅ | Playfair Display (headings) + Inter (body), Trust & Warm colours |

## 3. Tech Stack
- **Frontend:** semantic HTML5, CSS Grid / Flexbox, vanilla ES6 (no frameworks)
- **Fonts:** Google Fonts (Playfair Display, Inter)
- **Icons:** inline SVG / PNG (logos, maps pin)
- **Hosting:** static files (final zip hand-off)

## 4. User Stories
- As a **first-time visitor**, I want to see service times and location at a glance so I can plan my visit.
- As a **member**, I want the calendar to always show upcoming events so I don’t miss activities.
- As a **seeker**, I want to read the pastor’s story and beliefs so I can trust the church’s teachings.
- As a **ministry leader**, I want my ministry card displayed so newcomers can discover us.
- As the **webmaster**, I want a clean codebase that any volunteer can edit without build tools.

## 5. Nice-to-Haves (Post-MVP)
- Dark-mode toggle (saves to localStorage)
- Hamburger mobile menu
- Scroll-spy nav highlights
- Multi-language toggle (EN / JP)
- Sermon audio playlist page
- Online giving button (external link)