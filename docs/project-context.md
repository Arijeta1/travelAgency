# TravelAgency project context

TravelAgency is a WEB1 group project for travelers who know what kind of trip they want and need ideas about where to go. Visitors can discover places for history, culture, scenery, or outdoor activities and find destinations that suit their preferred weather.

## Visitor journey

Visitors can browse the catalog directly or take a short questionnaire about their interests, preferred weather, and travel month. The browser ranks destinations from a shared curated dataset and explains why each recommendation matched. Visitors can open a recommendation's details or compare destinations side by side.

## Planned pages

| Page | Purpose |
| --- | --- |
| `index.html` | Introduce the guide and offer entry points into browsing and the questionnaire. |
| `destinations.html` | Browse and filter destinations by interest. |
| `destination.html` | Show highlights, activities, and typical seasonal conditions for a selected destination. |
| `trip-finder.html` | Collect preferences, validate answers, and show ranked recommendations with match reasons. |
| `compare.html` | Compare selected destinations by climate, activities, and recommended travel months. |

## Recommendation approach

Use a shared dataset with stable destination IDs, interest tags, and typical conditions by month. Score how closely each destination fits the answers and show the strongest matching reasons. Give visitors a way to adjust their preferences when there is no strong match. Label weather information as typical seasonal conditions.

The main site runs in the browser with static files and client-side data. Accounts, bookings, and live weather are outside the first version. Trip Finder is the proposed page to recreate in the separate React exercise.
