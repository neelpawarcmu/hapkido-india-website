# Hapkido Federation India Website

A modern, responsive website for Hapkido Federation India, inspired by the World Taekwondo website design.

## Features

- **Modern Design**: Clean, professional design with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Enhanced navigation with smooth scroll effects
- **Interactive Elements**: Hover effects, animations, and dynamic interactions
- **All Required Sections**:
  - Home page with hero section
  - Introduction to Hapkido
  - Mission statement
  - Affiliation and certifications
  - Events and competitions
  - Gallery
  - About the masters
  - Contact form

## Getting Started

### Prerequisites

- Node.js (v14 or higher) - [Download here](https://nodejs.org/)
- npm (comes with Node.js)

### Installation

1. Clone or download this repository
2. Navigate to the project directory:
   ```bash
   cd hapkido-india-website
   ```

3. Install dependencies (optional, for local server):
   ```bash
   npm install
   ```

### Running Locally

#### Option 1: Using npm (Recommended)

```bash
npm start
```

This will start a local server at `http://localhost:8080` and automatically open it in your browser.

#### Option 2: Using Python (if you have Python installed)

```bash
# Python 3
python3 -m http.server 8080

# Python 2
python -m SimpleHTTPServer 8080
```

Then open your browser and navigate to `http://localhost:8080`

#### Option 3: Using PHP (if you have PHP installed)

```bash
php -S localhost:8080
```

Then open your browser and navigate to `http://localhost:8080`

#### Option 4: Direct File Opening

Simply open `index.html` in your web browser. Note that some features may work better with a local server.

## Project Structure

```
hapkido-india-website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript for interactivity
├── package.json        # npm configuration
└── README.md           # This file
```

## Adding Images

The website is set up to use images from the official Hapkido Federation India Instagram post. 

**See `IMAGE_SETUP.md` for detailed instructions on downloading and setting up images.**

Quick steps:
1. Download images from: https://www.instagram.com/p/DRyigFFDHrs/?img_index=1
2. Place logo in: `images/logo/hapkido-logo.png`
3. Place hero image in: `images/hero/hapkido-hero.jpg`
4. Place gallery images in: `images/gallery/`
5. Place master photos in: `images/masters/`

The website includes beautiful gradient fallbacks, so it will look great even while you're adding images!

## Customization

### Colors

The website uses traditional Hapkido colors (deep blues, vibrant reds, crisp whites). Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #0a1929;
    --secondary-color: #1e3a5f;
    --accent-color: #c8102e;
    --accent-red: #dc143c;
    --gold-color: #ffd700;
    /* ... */
}
```

### Content

- Edit `index.html` to update text content, images, and structure
- Replace placeholder images in the gallery and master sections with actual photos
- Update contact information, events, and other details

### Images

To add real images:
1. Create an `images` folder in the project root
2. Add your images to the folder
3. Update the `src` attributes in `index.html` to point to your images

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (no frameworks)
- Google Fonts (Inter)

## License

MIT License - feel free to use and modify as needed.

## Contact

For questions or support, please contact Hapkido Federation India.

---

**Note**: This is a static website. For production deployment, you may want to:
- Add a backend for the contact form
- Implement a CMS for easy content management
- Add image optimization
- Set up analytics
- Configure SEO settings

