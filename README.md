# Tooth to Tooth Mobile Dental Hygiene Clinic

This is the static website for Tooth to Tooth Mobile Dental Hygiene Clinic, migrated from Squarespace to GitHub Pages.

## Website Structure

- `index.html` - Landing page with language selection
- `en.html` - English version of the website
- `fr.html` - French version of the website
- `css/styles.css` - Main stylesheet
- `images/` - Directory for images (placeholder images can be replaced)

## Features

- Bilingual support (English/French)
- Responsive design
- Clean, modern layout
- Easy navigation
- Mobile-friendly

## Deployment to GitHub Pages

### 1. Create a GitHub Repository

```bash
# Initialize git repository
cd tooth-to-tooth-website
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: Tooth to Tooth website"
```

### 2. Push to GitHub

```bash
# Create a new repository on GitHub named 'toothtotoothmobile.com' or similar

# Add remote origin (replace with your repository URL)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch and "/ (root)" folder
5. Click "Save"
6. Your site will be published at: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

### 4. Custom Domain Setup (Optional)

To use the custom domain `toothtotoothmobile.com`:

1. In your repository settings under Pages, enter your custom domain
2. Create a `CNAME` file in the root directory with your domain name
3. Update your domain's DNS settings:
   - Add a CNAME record pointing to `YOUR-USERNAME.github.io`
   - Or add A records pointing to GitHub's IP addresses (see GitHub documentation)

## Updating Content

### To update the website:

1. Edit the HTML files (`en.html` or `fr.html`)
2. Commit your changes: `git commit -am "Update content"`
3. Push to GitHub: `git push`
4. Changes will be live within a few minutes

### To add images:

1. Add image files to the `images/` directory
2. Reference them in HTML: `<img src="images/your-image.jpg" alt="Description">`
3. Commit and push changes

## Maintenance

- The website is static HTML/CSS, requiring no server-side processing
- Updates are deployed via git push
- No database or backend maintenance required

## Contact Information

**Tooth to Tooth Mobile Dental Hygiene Clinic**
- Phone: (514) 431-1999
- Email: toothtotooth.mobile@gmail.com
- Address: 6600 Transcanadienne, Suite 510, Pointe-Claire, QC H9R 2S2
