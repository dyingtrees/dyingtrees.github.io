# Photography Portfolio - Setup Instructions

This is a simple, elegant photography portfolio website that you can host on GitHub Pages.

## Step-by-Step Setup Guide

### Step 1: Create a New Repository on GitHub

1. Go to https://github.com/dyingtrees
2. Click the green "New" button (or go to https://github.com/new)
3. Name your repository: `dyingtrees.github.io` (this exact name is important!)
4. Make sure it's set to "Public"
5. Check "Add a README file" (optional, but recommended)
6. Click "Create repository"

### Step 2: Upload Your Website Files

**Option A: Using GitHub's Web Interface (Easiest)**

1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
3. Create a folder called `images` by clicking "Add file" → "Create new file"
   - Type `images/placeholder.txt` and add any text
   - This creates the images folder
4. Upload your photos to the `images` folder
5. Commit the changes

**Option B: Using Git (If you're familiar with command line)**

```bash
# Clone your repository
git clone https://github.com/dyingtrees/dyingtrees.github.io.git
cd dyingtrees.github.io

# Add the website files
# (copy index.html and styles.css to this folder)

# Create images folder and add your photos
mkdir images
# (copy your photos to the images folder)

# Commit and push
git add .
git commit -m "Initial portfolio website"
git push
```

### Step 3: Prepare Your Images

Before uploading your photos:

1. **Resize your images** for web (recommended: 1200-2000px on the longest side)
2. **Compress them** using tools like:
   - TinyPNG (https://tinypng.com/)
   - ImageOptim (Mac)
   - Squoosh (https://squoosh.app/)
3. **Name them clearly**: `photo1.jpg`, `photo2.jpg`, etc.
4. Save a larger image for the hero section and name it `hero.jpg`

### Step 4: Customize the Website

Edit `index.html` to personalize:

1. Replace "Your Name" with your actual name
2. Update the page title
3. Add/remove gallery items as needed
4. Write your "About" section
5. Add your contact information
6. Update the number of images in the gallery section

### Step 5: Enable GitHub Pages

1. Go to your repository settings
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait a few minutes for your site to build

### Step 6: View Your Website

Your website will be live at: `https://dyingtrees.github.io`

It may take 5-10 minutes for changes to appear after you first enable GitHub Pages.

## File Structure

Your repository should look like this:

```
dyingtrees.github.io/
├── index.html
├── styles.css
├── images/
│   ├── hero.jpg
│   ├── photo1.jpg
│   ├── photo2.jpg
│   ├── photo3.jpg
│   ├── photo4.jpg
│   ├── photo5.jpg
│   └── photo6.jpg
└── README.md
```

## Making Changes

After your site is live, you can make changes by:

1. Editing files directly on GitHub (click the pencil icon)
2. Or, if using Git locally, make changes and push:
   ```bash
   git add .
   git commit -m "Update gallery"
   git push
   ```

Changes will appear on your site within a few minutes.

## Tips

- **Image optimization is crucial** - large images will make your site slow
- Keep total repository size under 1GB (GitHub's limit)
- You can add more pages by creating new HTML files
- Consider adding a favicon for a professional touch
- Test your site on mobile devices

## Optional Enhancements

- Add a lightbox for full-size image viewing
- Create separate pages for different photography categories
- Add social media links
- Use a custom domain name
- Add smooth scrolling animations

## Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- Feel free to customize the HTML and CSS to match your style!

Enjoy showcasing your photography!
