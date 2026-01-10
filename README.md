# Wilson Lab Website

Modern, responsive website for the Wilson Lab at Boston University's Center for Regenerative Medicine.

## Quick Start Guide

### 1. File Structure
```
wilson-lab-website/
├── index.html           # Homepage
├── team.html           # Team members page
├── research.html       # Research areas page
├── publications.html   # Publications list
├── datasets.html       # Interactive datasets
├── contact.html        # Contact information
├── styles.css          # All styling
├── script.js           # JavaScript functionality
├── images/            # Image folder (create this)
│   ├── team-photo.jpg
│   ├── placeholder-person.jpg
│   ├── placeholder-research.jpg
│   └── [individual team member photos]
└── files/             # Downloadable files (create this)
    └── [dataset files]
```

## Setting Up GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to https://github.com and sign in
2. Click the "+" icon in top right → "New repository"
3. Name it `wilsonlab` (or any name you prefer)
4. Make it **Public**
5. **Don't** initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Upload Your Website Files
**Option A - Using GitHub Web Interface (Easiest):**
1. On your new repository page, click "uploading an existing file"
2. Drag and drop ALL your website files:
   - index.html
   - team.html
   - research.html
   - publications.html
   - datasets.html
   - contact.html
   - styles.css
   - script.js
3. Create folders by clicking "Add file" → "Create new file"
   - Type `images/placeholder.txt` and commit
   - Type `files/placeholder.txt` and commit
4. Scroll down and click "Commit changes"

**Option B - Using Git Command Line:**
```bash
# In your website folder
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/wilsonlab.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. In your repository, click "Settings" (top right)
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes, then visit: `https://YOUR-USERNAME.github.io/wilsonlab/`

### Step 4: Point Your GoDaddy Domain
1. In GoDaddy, go to your domain settings
2. Find "DNS Management" or "Manage DNS"
3. Add/Edit these records:
   - **A Record**: Point to `185.199.108.153`
   - **A Record**: Point to `185.199.109.153`
   - **A Record**: Point to `185.199.110.153`
   - **A Record**: Point to `185.199.111.153`
   - **CNAME Record**: `www` → `YOUR-USERNAME.github.io`
4. In GitHub repository settings → Pages, add your custom domain
5. Wait 24-48 hours for DNS to propagate

## Adding Your Images

### Image Requirements
- **Team photo (homepage):** 1200x800px recommended
- **Individual portraits:** 300x300px square recommended
- **Research images:** 800x600px recommended

### How to Add Images
1. Go to your GitHub repository
2. Click into the `images` folder
3. Click "Add file" → "Upload files"
4. Drag your images
5. Name them exactly as referenced in the HTML:
   - `team-photo.jpg` (main team photo)
   - `andrew-wilson.jpg`
   - `joe-kaserman.jpg`
   - `carly-merritt.jpg`
   - `meline-homps.jpg`
   - `mark-dodge.jpg`
   - `marissa-gallagher.jpg`
   - `vikram-daesety.jpg`
   - Research images as needed

### Creating Placeholder Images
If you don't have images ready:
1. Use https://placehold.co/ to generate placeholders
2. For portraits: `https://placehold.co/300x300/1a3a52/white?text=Name`
3. For research: `https://placehold.co/800x600/1a3a52/white?text=Research`

## Updating Content

### Adding/Removing Team Members
1. Open `team.html` in any text editor
2. Find the `<div class="team-grid">` section
3. Copy an existing team member block:
```html
<div class="team-member">
    <div class="member-photo">
        <img src="images/NAME.jpg" alt="Full Name" />
    </div>
    <div class="member-info">
        <h3>Full Name, Degree</h3>
        <p class="member-title">Title</p>
        <p class="member-education">Education</p>
        <p class="member-research"><strong>Research Interests:</strong> Description</p>
        <p class="member-contact">email at bu.edu</p>
    </div>
</div>
```
4. Edit the information
5. Save and upload to GitHub

### Adding Publications
1. Open `publications.html`
2. Find the `<ol class="publication-list">` section
3. Add a new `<li class="publication-item">` at the top:
```html
<li class="publication-item">
    <span class="authors">Author et al.</span>
    <a href="URL" target="_blank" class="title">Title of paper.</a>
    <span class="journal">Journal Name.</span>
    <span class="year">2024</span>
    <span class="pmid">PMID: 12345678.</span>
</li>
```

### Changing Colors
In `styles.css`, edit the CSS variables at the top:
```css
:root {
    --primary: #1a3a52;      /* Main dark blue */
    --accent: #d4a574;       /* Gold accent */
    --bg-light: #fafaf8;     /* Light background */
}
```

## Troubleshooting

**Website not showing up?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check Settings → Pages shows "Your site is published at..."
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)

**Images not loading?**
- Check file names match exactly (case-sensitive!)
- Ensure images are in the `images` folder
- Check image file extensions (.jpg, .png, etc.)

**Need to make changes?**
1. Edit files locally on your computer
2. Go to GitHub repository → "Add file" → "Upload files"
3. Upload the changed file (it will replace the old one)
4. Wait 1-2 minutes for changes to appear

## Support Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML Tutorial](https://www.w3schools.com/html/)
- [GitHub Desktop App](https://desktop.github.com/) - Easier than command line

## Contact
For questions about the website, contact your web developer or refer to GitHub's documentation.
