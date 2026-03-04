# Manila Zoo: The New AI-Era

**A Smart Park Experience Redefining Wildlife Conservation in the Philippines.**

---

## Overview

This repository contains the web platform for the redeveloped Manila Zoo. Built as a high-performance **Single Page Application (SPA)**, the platform integrates real-time AI capabilities, interactive mapping, and a fully responsive interface designed for the modern visitor.

## Key Features

* **AI Smart Ranger:** Voice-activated AI concierge powered by ElevenLabs Conversational AI SDK for real-time guest assistance and tab navigation via voice commands.
* **Dynamic Itinerary Planner:** AI-generated park itineraries based on visitor group size and interests, displayed as an animated timeline.
* **Interactive 3D Map:** Custom coordinate system with clickable zone pins, info popups, and zone-specific data overlays on a hand-illustrated park map.
* **Wildlife Directory:** 16 animal species with detailed cards — conservation status, habitat, diet, population data, and high-resolution images.
* **Mobile-First Responsive:** Full responsive design with hamburger navigation, stacked layouts, and a dedicated small-screen breakpoint (< 400px).
* **Optimized Performance:** SPA architecture with zero-reload transitions, deferred animations, and optimized video (54.6 MB).

## Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Glassmorphism), JavaScript (ES6+) |
| **AI / Voice** | ElevenLabs Conversational AI SDK |
| **Typography** | Chewy (branding) + Plus Jakarta Sans (body) |
| **Animation** | CSS Keyframes, DOM Physics Engine, Falling Leaves |
| **Responsive** | CSS Media Queries (768px, 400px breakpoints) |

## Project Structure

```
manila-zoo-spa/
├── index.html                  # Single-page app (~2,600 lines)
├── bg_video.mp4                # Hero background video (54.6 MB)
├── map-3d.jpg                  # Illustrated park map
├── Manila Zooknowledgebase.txt # AI ranger knowledge base
├── progress.md                 # Development progress tracker
├── assets/                     # 16 animal images (PNG/JPEG)
│   ├── eagle.png
│   ├── tamaraw.png
│   ├── tiger.png
│   └── ... (13 more)
└── oldfiles/                   # Legacy multi-page HTML (archived)
    ├── animals.html
    ├── conservation.html
    ├── map.html
    └── tickets.html
```

## SPA Views

| View | Description |
| :--- | :--- |
| **Home** | Hero video, contact widget, app download section with phone mockup |
| **Our Animals** | Grid of 16 animal cards with conservation status badges |
| **Interactive Map** | Sidebar zone list + illustrated map with clickable pins & info popups |
| **Conservation** | Mission cards for reforestation, species breeding, and education |
| **Buy Tickets** | Ticket pricing cards + AI Smart Itinerary planner with timeline output |

## Installation & Deployment

1. **Clone the repository:**
   ```bash
   git clone https://github.com/brub-ai/manila-zoo-spa.git
   cd manila-zoo-spa
   ```

2. **Setup:**
   Ensure `bg_video.mp4` and `map-3d.jpg` are present in the root directory.

3. **Run:**
   Open `index.html` in any modern browser or deploy via GitHub Pages / Vercel.

## Development

See [progress.md](progress.md) for detailed development history and session-by-session changes.
