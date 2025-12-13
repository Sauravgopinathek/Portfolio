# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ✨ Smooth animations and transitions
- 🎯 Easy to customize
- 🚀 Fast and lightweight

## Sections

- **Hero**: Eye-catching introduction with call-to-action buttons
- **About**: Tell your story and background
- **Projects**: Showcase your work with project cards
- **Skills**: Display your technical skills organized by category
- **Contact**: Multiple ways for people to reach you

## Customization

### Update Your Information

1. **Personal Details** (in `index.html`):
   - Replace "Your Name" with your actual name
   - Update the subtitle and description in the hero section
   - Add your email, GitHub, and LinkedIn links in the contact section

2. **Projects** (in `index.html`):
   - Replace placeholder projects with your actual projects
   - Update project titles, descriptions, and tags
   - Add links to live demos and GitHub repositories
   - Replace placeholder images with actual project screenshots

3. **Skills** (in `index.html`):
   - Modify the skills lists to match your expertise
   - Add or remove skill categories as needed

4. **Colors** (in `styles.css`):
   - Modify the CSS variables in `:root` to change the color scheme
   - Primary color: `--primary-color`
   - Secondary color: `--secondary-color`

### Adding Project Images

Replace the placeholder images by:
1. Adding your project screenshots to an `images/` folder
2. Updating the `.project-image` divs in `index.html`:
   ```html
   <div class="project-image">
       <img src="images/your-project.jpg" alt="Project Name">
   </div>
   ```

## Running Locally

Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using VS Code Live Server extension
# Right-click on index.html and select "Open with Live Server"
```

## Deployment

You can deploy this portfolio to:
- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Drag and drop deployment
- **Vercel**: Easy deployment with custom domains
- **Any static hosting service**

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your own portfolio!

---

**Good luck with your portfolio! 🚀**

Deployment Link - https://lighthearted-sable-f7e9c6.netlify.app/

