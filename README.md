# Portfolio Website

A modern, responsive portfolio website to showcase your projects and work.

## Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Animated hero section with typing effect
- Project showcase grid
- Mobile-friendly hamburger menu
- Modern gradient design
- Scroll animations

## Customization

Before deploying, customize the following in `index.html`:

1. **Personal Information**
   - Replace "Your Name" in the hero section
   - Update the tagline "Developer | Designer | Creator"
   - Add your bio in the About section

2. **Projects**
   - Replace placeholder projects with your actual work
   - Add project images (replace the placeholder divs)
   - Update project descriptions and links
   - Modify technology tags to match your projects

3. **Contact Information**
   - Update email link
   - Add your GitHub profile URL
   - Add your LinkedIn profile URL

4. **Skills**
   - Modify skill tags to match your expertise
   - Add or remove technologies as needed

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - For a user site: `username.github.io`
   - For a project site: any name you want
3. Don't initialize with README (we already have one)

### Step 2: Push Your Code

Run these commands in your terminal:

```bash
# Add all files to git
git add .

# Commit your changes
git commit -m "Initial portfolio website commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/your-username/your-repo-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at `https://your-username.github.io/your-repo-name/`

### Step 4: Wait for Deployment

GitHub Pages typically takes 1-5 minutes to deploy. Once done, visit your URL to see your portfolio live!

## Local Development

To view your portfolio locally:

1. Simply open `index.html` in your web browser
2. Or use a local server (recommended for full functionality):

```bash
# If you have Python installed
python -m http.server 8000

# If you have Node.js installed
npx serve

# Then visit http://localhost:8000 in your browser
```

## Adding Project Images

1. Create an `images` folder in your project
2. Add your project screenshots
3. Replace the placeholder divs in `index.html`:

```html
<!-- Replace this: -->
<div class="placeholder-image">Project Image</div>

<!-- With this: -->
<img src="images/project1.png" alt="Project 1">
```

## File Structure

```
Porto/
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── script.js           # Interactive features and animations
└── README.md           # This file
```

## Browser Support

This portfolio works on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Tips for Success

1. **Add Real Projects**: Replace the placeholder projects with your actual work
2. **Use Good Images**: Add high-quality screenshots of your projects
3. **Keep it Updated**: Regularly update with new projects and skills
4. **SEO Optimization**: Update the meta description in `index.html`
5. **Personal Touch**: Customize colors in `styles.css` to match your personal brand

## Troubleshooting

**Site not showing up?**
- Make sure GitHub Pages is enabled in repository settings
- Check that files are in the main branch
- Wait a few minutes for GitHub to build and deploy

**Styling looks broken?**
- Ensure `styles.css` and `script.js` are in the same directory as `index.html`
- Check browser console for any errors

**Links not working?**
- Update all placeholder URLs with your actual links
- Ensure URLs include `https://`

## Next Steps

1. Customize the content with your information
2. Add your project images
3. Test locally
4. Push to GitHub
5. Enable GitHub Pages
6. Share your portfolio URL!

## License

Feel free to use this template for your own portfolio. No attribution required.
