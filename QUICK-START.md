# Wilson Lab Website - Quick Start Guide

Your new website is ready! Here's what you have and what to do next.

## ✅ What's Included

- **7 HTML Pages**: Home, Team, Research, Publications, Datasets, Contact
- **Modern Design**: Clean, professional styling with your lab's content
- **Mobile Responsive**: Works perfectly on phones, tablets, and desktops
- **Easy to Update**: Simple HTML that you can edit
- **Placeholder Images**: Temporary images until you add your own

## 🚀 Next Steps (In Order)

### 1. Download All Files (5 minutes)
- Download this entire folder to your computer
- Keep the structure intact (don't move files around)

### 2. Set Up GitHub Account (10 minutes)
If you don't have one:
- Go to https://github.com
- Click "Sign up"
- Choose a username (suggestion: "wilsonlab-bu" or your name)
- Verify your email

### 3. Create Repository & Upload (15 minutes)
**Easy Method (Recommended):**
1. Log into GitHub
2. Click the "+" icon (top right) → "New repository"
3. Name: `wilsonlab` (or anything you want)
4. Make it **Public**
5. Click "Create repository"
6. Click "uploading an existing file"
7. Drag ALL the website files into the box
8. Click "Commit changes"

**You now have your files on GitHub!**

### 4. Enable GitHub Pages (2 minutes)
1. In your repository, click "Settings" (top menu)
2. Click "Pages" (left sidebar)
3. Under "Source", select "main" branch
4. Click "Save"
5. **Wait 2 minutes**, then your site is live at:
   `https://YOUR-USERNAME.github.io/wilsonlab/`

### 5. Add Your Images (Ongoing)
Replace the placeholder images in the `images` folder:
1. Go to your repository on GitHub
2. Click the `images` folder
3. Click "Add file" → "Upload files"
4. Upload your photos (see images/README.md for required names)

**Important**: Name your images exactly as specified:
- `team-photo.jpg` - Main group photo
- `andrew-wilson.jpg` - Your portrait
- Individual team member portraits

### 6. Point Your GoDaddy Domain (Optional, 30 minutes)
See the full README.md file for detailed DNS instructions.

Quick version:
1. GoDaddy → Your domain → DNS Management
2. Add GitHub's IP addresses as A records
3. Add CNAME record for www
4. In GitHub Settings → Pages, add your custom domain

## 📝 Making Updates

### To Update Content:
1. Open the HTML file in any text editor (Notepad, TextEdit, VS Code)
2. Make your changes
3. Save the file
4. Upload to GitHub (replaces old version)
5. Wait 1-2 minutes to see changes

### Common Updates:

**Add a team member:**
- Edit `team.html`
- Copy an existing member block
- Change the information
- Upload new photo to `images/`

**Add a publication:**
- Edit `publications.html`
- Add a new `<li>` item at the top of the list
- Follow the existing format

**Change colors:**
- Edit `styles.css`
- Find the `:root` section at the top
- Change the color codes

## 🆘 Troubleshooting

**"My site isn't showing up"**
- Wait 2-3 minutes after enabling GitHub Pages
- Check Settings → Pages for the published URL
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)

**"Images aren't loading"**
- File names must match EXACTLY (case-sensitive)
- Check images are in the `images` folder
- Use .jpg or .png extensions

**"I made changes but don't see them"**
- Wait 1-2 minutes (GitHub Pages needs to rebuild)
- Clear browser cache
- Check you uploaded the correct file

## 📚 Resources

- **GitHub Pages Docs**: https://docs.github.com/en/pages
- **HTML Tutorial**: https://www.w3schools.com/html/
- **GitHub Desktop** (easier than command line): https://desktop.github.com/

## 💡 Tips

1. **Make backups**: Keep a copy of your files on your computer
2. **Test locally**: Open the HTML files in your browser before uploading
3. **Small changes**: Make one change at a time, easier to troubleshoot
4. **Use GitHub Desktop**: It's much easier than the command line

## Need Help?

1. Check the full README.md file
2. Ask a tech-savvy colleague
3. GitHub has excellent documentation
4. Consider hiring a student for ongoing updates

---

**You're all set!** Your website is modern, professional, and ready to go live. Start with Step 1 above and you'll be online in under an hour.
