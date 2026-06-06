# The Property — A Rare Offering

A luxury real estate landing page featuring a scroll-driven frame animation experience. Built with vanilla HTML, CSS, and JavaScript.

## Live Demo
🌐 [View Live on Vercel](https://property-page.vercel.app)

## Features
- Scroll-driven frame-by-frame animation (475 frames)
- Custom animated cursor
- Film grain overlay
- Elegant loading screen with progress bar
- Hero text reveal on scroll completion
- Responsive contact/enquiry form
- Luxury typography with Cormorant Garamond & Jost
- Fully responsive design

## Tech Stack
- **Frontend:** Vanilla HTML, CSS, JavaScript
- **Animation:** Canvas API + JSZip
- **Fonts:** Google Fonts (Cormorant Garamond, Jost)
- **Frame Storage:** Hugging Face Datasets (356 MB zip)
- **Deployment:** Vercel

## Project Structure
```
property-page/
├── index.html        # Main page (all CSS + JS inline)
└── README.md
```

## How It Works
The animation loads 475 PNG frames from a zip file hosted on Hugging Face. As the user scrolls, the canvas renders each frame in sequence — creating a cinematic scroll experience. The hero text fades in over the final 30 frames.

## Frame Hosting
Frames are stored on Hugging Face:
```
https://huggingface.co/datasets/vesastudios/property-frames/resolve/main/combined_frames.zip
```

## Deploy on Vercel
1. Fork or clone this repo
2. Go to [vercel.com](https://vercel.com)
3. Import the GitHub repo `vedant-B22/property-page`
4. No build settings needed — it's a static site
5. Click **Deploy**

## Local Development
```bash
# Clone the repo
git clone https://github.com/vedant-B22/property-page.git
cd property-page

# Start local server
python -m http.server 8000

# Open in browser
http://localhost:8000
```

## Credits
Designed & built by [Vesa Studios](https://vesastudios.site)
