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



## API Endpoints
- **GET /api/events**: List all events.
- **GET /api/events/upcoming**: List upcoming events.
- **GET /api/events/past**: List past events.
- **GET /api/events/live**: Get live stream status.
- **Response Format**: JSON array of event objects (see schema for example).






# ETHNigeria 2025 Careers Page Schema

## Overview
This schema defines the careers page for ethnigeria.org/careers, recruiting interns, volunteers, and showcasing partner opportunities with Nigerian cultural elements (Adire, Uli, Hausa motifs).

## Usage
- **Framework**: Next.js with Tailwind CSS.
- **API**: Fetch roles from `/api/careers`, partners from `/api/partners`, submit applications to `/api/careers/apply`.
- **Form**: Use React Hook Form, AWS S3 for resume uploads.
- **Dependencies**: Google Analytics, Tailwind CSS.

## Key Sections
- **Hero**: Banner with Adire patterns and CTA.
- **Opportunities**: Cards for internships, volunteers, partners with cultural animations.
- **Application Form**: Dynamic form with role dropdowns and file uploads.
- **Partners**: Logo grid with cultural borders.

## Notes
- Test form submissions and performance in Nigeria’s network.
- Coordinate with graphic designer for cultural assets.
- Ensure WCAG 2.1 accessibility.
