# GMBRank (GBP Rank Tracker)

A **Google Business Profile (GBP) Rank Tracking web application** — a single-page application (SPA) that helps businesses monitor how their Google Business Profile ranks in local search results for specific keywords.

> **Note:** "GBP" = Google Business Profile (formerly Google My Business / GMB)

## Core Functionality

| Feature | Description |
|---------|-------------|
| **User Authentication** | Login/Register system with session-based auth |
| **Business Management** | Add and manage multiple business locations |
| **Keyword Sets** | Create keyword groups to track per business |
| **Rank Checking** | Check/search current ranking positions for keywords |
| **Statistics & Trends** | View ranking history with trend indicators (↑ ↓ →) |
| **Dashboard** | Overview of rankings with visual position indicators |

## Key UI Sections

- **Dashboard (Home)** — Main overview with business/location/keyword set selectors
- **Rank Check** — Run new ranking checks with date selection
- **Stats** — Historical performance analytics

## Technical Details

| Aspect | Implementation |
|--------|---------------|
| **Frontend** | Vanilla JavaScript SPA (no framework) |
| **Styling** | Custom CSS with Google Fonts (Syne, DM Mono, DM Sans) |
| **API** | RESTful JSON API at `/api/*` endpoints |
| **Auth** | Cookie-based sessions (`credentials: 'include'`) |

## File Structure

| File | Purpose |
|------|---------|
| `index.html` | Main SPA shell — auth page + app layout |
| `app.js` | Core application logic — routing, API calls, state management, DOM rendering |
| `style.css` | All custom styling |

## API Endpoints Used (inferred)

