# -ethnigeria-website
Schema for ETH Nigeria Developers'
# ETHNigeria 2025 Events Page Schema

## Overview
This schema defines the structure for the ETHNigeria 2025 website's events page (ethnigeria.org/events). It includes sections for a hero banner, search bar, event map, upcoming/past events, live stream, and CTA, with Nigerian cultural elements (Yoruba Adire, Igbo Uli, Hausa motifs).

## Usage
- **Framework**: Implement with Next.js for SEO and performance.
- **API**: Fetch event data from `/api/events`, `/api/events/upcoming`, `/api/events/past`, `/api/events/live`.
- **Cultural Assets**: Coordinate with graphic designer for Adire, Uli, and Hausa motif assets.
- **Dependencies**: Leaflet.js for map, YouTube API for live stream, Tailwind CSS for styling.

## Key Sections
- **Hero**: Banner with Adire patterns and talking drum animation.
- **Event Map**: Interactive map with cultural pins (e.g., Yoruba drum for Lagos).
- **Live Stream**: YouTube/StreamYard integration with Igbo Uli frame.

## API Example
```json
[
  {
    "id": "ethnigeria-2025",
    "title": "ETHNigeria 2025",
    "date": "2025-08-01",
    "location": "Lagos, Nigeria",
    "coordinates": [6.5244, 3.3792],
    "type": "Conference",
    "cultural_element": "Yoruba talking drum animation"
  }
]
