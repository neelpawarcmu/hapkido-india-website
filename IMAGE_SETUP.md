# Image Setup Guide

This guide will help you download images from the Instagram post and set them up for the website.

## Instagram Post
**URL**: https://www.instagram.com/p/DRyigFFDHrs/?img_index=1

## How to Download Images from Instagram

### Method 1: Using Browser (Easiest)
1. Open the Instagram post in your web browser
2. Right-click on each image
3. Select "Save Image As..." or "Download Image"
4. Save with the appropriate filename (see below)

### Method 2: Using Instagram Downloader Tools
- Use online tools like:
  - https://downloadgram.org/
  - https://instadownloader.co/
  - https://www.instadownloader.com/
1. Paste the Instagram post URL
2. Download all images
3. Rename them according to the structure below

### Method 3: Using Browser Developer Tools
1. Open Instagram post in browser
2. Press F12 to open Developer Tools
3. Go to Network tab
4. Filter by "Images"
5. Refresh the page
6. Find the image URLs and download them

## Required Images and File Structure

Place images in the following folders with these exact filenames:

### Logo
- **Location**: `images/logo/hapkido-logo.png`
- **Description**: Official Hapkido Federation India logo
- **Recommended size**: 200x50px to 400x100px (maintain aspect ratio)
- **Format**: PNG with transparent background preferred

### Hero Section
- **Location**: `images/hero/hapkido-hero.jpg`
- **Description**: Main hero/background image for homepage
- **Recommended size**: 1920x1080px or larger
- **Format**: JPG

### Gallery Images
Place these in `images/gallery/`:
- `training-session.jpg` - Training session photo
- `belt-ceremony.jpg` - Belt ceremony/graduation photo
- `competition.jpg` - Competition or tournament photo
- `weapons-training.jpg` - Weapons training demonstration
- `master-demo.jpg` - Master demonstration
- `group-training.jpg` - Group training session

**Recommended size**: 1200x800px or larger
**Format**: JPG

### Master Photos
Place these in `images/masters/`:
- `grandmaster-kim.jpg` - Grandmaster Kim photo
- `master-park.jpg` - Master Park photo
- `master-lee.jpg` - Master Lee photo

**Recommended size**: 600x800px (portrait orientation)
**Format**: JPG

## Image Optimization Tips

1. **Compress images** before uploading to reduce file size:
   - Use tools like TinyPNG, ImageOptim, or Squoosh
   - Aim for file sizes under 500KB for web images

2. **Maintain aspect ratios**:
   - Gallery images: 3:2 or 4:3 ratio
   - Master photos: 3:4 or 2:3 ratio (portrait)
   - Hero image: 16:9 ratio

3. **File naming**:
   - Use lowercase letters
   - Use hyphens instead of spaces
   - Keep names descriptive but short

## Quick Setup Checklist

- [ ] Download logo from Instagram post → `images/logo/hapkido-logo.png`
- [ ] Download hero image → `images/hero/hapkido-hero.jpg`
- [ ] Download 6 gallery images → `images/gallery/`
- [ ] Download 3 master photos → `images/masters/`
- [ ] Optimize all images for web
- [ ] Test website to ensure all images load correctly

## Fallback Behavior

The website is designed with fallback gradients, so if an image is missing:
- The logo will show the text "Hapkido Federation India"
- Gallery items will show colorful gradient placeholders
- Master photos will show gradient placeholders
- Hero section will use a gradient background

This ensures the website always looks good, even while you're adding images!

## Need Help?

If you have trouble downloading images, you can:
1. Take screenshots of the Instagram post
2. Use the screenshots temporarily
3. Replace them with higher quality images later

The website will work perfectly with placeholder images until you add the real ones.

