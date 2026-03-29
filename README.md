# My Family Website

A beautiful, responsive family website showcasing family members, memories, and values. Built with modern HTML and CSS featuring a dark theme with warm accents.

## Features

✨ **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices

👨‍👩‍👧‍👦 **Family Members Section** - Display family member information with custom avatars and descriptions

📸 **Photo Gallery** - Organized photo grid with 60+ family photos in a 3-column layout

💭 **Memory Wall** - Highlight favorite family moments and traditions

📖 **Family Values** - Share what your family stands for (Love, Respect, Togetherness)

🎨 **Dark Theme** - Modern deep color palette with excellent contrast and readability

🔗 **Social Media Links** - Footer with links to Facebook, Instagram, GitHub, and LinkedIn

🎯 **Favicon** - Custom circular profile image as favicon

## Project Structure

```
My Family/
├── index.html          # Main family page
├── photos.html         # Dedicated photo gallery
├── Photos/             # Directory containing all family photos
│   ├── me.jpg
│   ├── ss.png
│   └── ... (60+ more photos)
└── README.md          # This file
```

## Pages

### Index (Home)
- Hero section with family introduction
- Family members cards
- Family values section
- Favorite family moments
- Family album link
- Social media footer

### Photos
- Compact 3-column photo grid
- 60+ family photos displayed with efficient layout
- Height optimized (60px) for viewing multiple photos
- Back link to home page
- Social media footer

## Color Scheme

**Dark Theme:**
- Background: `#1a1410` (Deep brown-black)
- Primary: `#d4685f` (Warm coral)
- Secondary: `#f5a962` (Golden orange)
- Accent: `#6fa86d` (Forest green)
- Text: `#f5f0eb` (Light cream)

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Responsive design with flexbox and grid
- **Font Awesome 6.4.0** - Social media icons
- **Responsive Meta Tags** - Mobile optimization

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/rameshwaryar77-lgtm/my-family.git
   cd my-family
   ```

2. Open in a browser:
   - Open `index.html` in your web browser
   - Or use a local server for best results:
     ```bash
     python -m http.server 8000
     # or
     npx http-server
     ```

3. Customize:
   - Edit family member information in `index.html`
   - Add your own photos to the `Photos/` folder
   - Update social media links in both HTML files
   - Modify colors in the CSS `:root` variables

## Customization Guide

### Change Family Members
Edit the "Family Members" section in `index.html`:
```html
<article class="card">
  <div class="avatar">D</div>
  <h3>Father</h3>
  <p>Your description here</p>
</article>
```

### Add More Photos
1. Save photos to `Photos/` folder
2. Add new photo-frame divs in `photos.html`
3. Update the grid layout if needed

### Update Social Links
Replace the URLs in footer social links with your own profiles:
```html
<a href="YOUR_FACEBOOK_URL" class="social-icon" title="Facebook">
  <i class="fab fa-facebook-f"></i>
</a>
```

### Change Colors
Edit the CSS variables in `:root`:
```css
:root {
  --bg: #1a1410;           /* Background color */
  --primary: #d4685f;      /* Primary color */
  --secondary: #f5a962;    /* Secondary color */
  --accent: #6fa86d;       /* Accent color */
  --text: #f5f0eb;        /* Text color */
}
```

## Browser Support

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Showcase

### Responsive Grid
- Home page: 4-column grid on desktop, 2 columns on tablet, 1 column on mobile
- Photos page: 3-column grid for optimal photo viewing

### Smooth Interactions
- Hover effects on cards and buttons
- Smooth transitions and animations
- Transform effects on social icons

### Accessibility
- Semantic HTML structure
- Proper color contrast
- Readable font sizes
- Alt text for images

## Future Enhancements

- [ ] Add contact form
- [ ] Implement photo filtering/search
- [ ] Add photo lightbox/modal
- [ ] Create timeline of family events
- [ ] Add family tree visualization
- [ ] Implement dark/light mode toggle

## License

This project is open source and available under the MIT License.

## Author

Created with ❤️ for the family

**GitHub:** [rameshwaryar77-lgtm](https://github.com/rameshwaryar77-lgtm)

---

**Want to create your own family website?** This template can be easily customized with your own content and photos!
