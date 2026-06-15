# W2-Homework3
# Cootels 🌿

A nature-themed cottage hotel landing page built with HTML and Tailwind CSS.

## Overview

Cootels is a static landing page for a cozy cottage hotel in Norway. It showcases the hotel's rooms, activities, organic food, and booking information.

## Features

- Responsive navigation bar with links and a CTA button
- Hero section with nature imagery
- Hotel story / about section
- Cabin Activities section
- 100% Organic Food section
- Room selection (Single, Double, Cottage)
- Step-by-step "How to Get My Room?" guide
- Customer testimonials section

## Tech Stack

- **HTML5**
- **Tailwind CSS** (compiled via CLI to `src/output.css`)

## Project Structure

```
cootels/
├── index.html
└── src/
    ├── input.css
    ├── output.css        # Compiled Tailwind CSS
    └── images/
        ├── Cootels.png
        ├── meritt-thomas-u-Hb93V6IWI-unsplash 1.png
        ├── meritt-thomas-u-Hb93V6IWI-unsplash 2.png
        ├── meritt-thomas-u-Hb93V6IWI-unsplash 3.png
        ├── image 10.png
        ├── image 11 (1).png
        ├── image 13.png
        ├── image 18 (1).png
        ├── image 21 (1).png
        └── ian-keefe-OgcJIKRnRC8-unsplash 1.png
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- Tailwind CSS CLI

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cootels.git
   cd cootels
   ```

2. Install Tailwind CSS:
   ```bash
   npm install -D tailwindcss
   ```

3. Build the CSS:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

4. Open `index.html` in your browser.

## Development

To watch for changes and rebuild automatically:

```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

> **Note:** If you add new Tailwind classes, you must rebuild `output.css` for them to take effect. Alternatively, swap the `<link>` tag in `<head>` for the Tailwind CDN during development:
> ```html
> ```

## Color Palette

| Name | Hex |
|------|-----|
| Navy Dark | `#192252` |
| Navy Light | `#424F7B` |
| Text Gray | `#848FAC` |
| Orange Accent | `#FF620A` |
| Button Dark | `#0E1734` |

## License

This project is for educational/portfolio purposes.
made by 
Muhammajon Nozilshoev 