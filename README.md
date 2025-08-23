# CabBook Landing Page

A modern, responsive landing page for the CabBook taxi booking app. Built with HTML, CSS, and JavaScript.

## 🚀 Features

- **Modern Design**: Clean, professional layout with your brand color (#7497fd)
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle hover effects and scroll animations
- **Mobile Menu**: Hamburger menu for mobile navigation
- **Contact Integration**: Direct email link to cabbook-support@proton.me
- **App Screenshots**: Showcase your app with the uploaded screenshots
- **SEO Optimized**: Proper meta tags and semantic HTML

## 📁 Project Structure

```
cabbook-landing/
├── index.html          # Main landing page
├── styles.css          # All styling and responsive design
├── script.js           # Interactive features and animations
├── assets/             # App screenshots
│   ├── app-store1.png
│   ├── app-store2.png
│   └── app-store3.png
└── README.md           # This file
```

## 🎨 Customization

### Colors
The main brand color is set to `#7497fd`. You can easily change this by editing the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #7497fd;    /* Your brand color */
    --primary-dark: #5a7af0;     /* Darker shade for hover states */
    --primary-light: #8ba8ff;    /* Lighter shade for accents */
}
```

### Content
- **App Name**: Change "CabBook" throughout the HTML
- **Taglines**: Update the hero subtitle and descriptions
- **Features**: Modify the feature cards in the features section
- **Contact Email**: Currently set to `cabbook-support@proton.me`

## 🌐 Deploying to GitHub Pages

### Step 1: Push to GitHub
1. Create a new repository on GitHub
2. Push your code to the repository:
```bash
git init
git add .
git commit -m "Initial commit: CabBook landing page"
git branch -M main
git remote add origin https://github.com/yourusername/cabbook-landing.git
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/(root)** folder
6. Click **Save**

Your site will be available at: `https://yourusername.github.io/cabbook-landing`

## 📱 Mobile Optimization

The landing page is fully optimized for mobile devices with:
- Responsive grid layouts
- Mobile-first navigation
- Touch-friendly buttons
- Optimized image loading
- Proper viewport settings

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance Features

- **Fast Loading**: Optimized CSS and minimal JavaScript
- **Smooth Scrolling**: Native smooth scroll behavior
- **Lazy Loading**: Images load with fade-in effects
- **Intersection Observer**: Efficient scroll animations
- **CSS Variables**: Easy theming and maintenance

## 🎯 Next Steps

### Optional Enhancements:
1. **Add App Store Links**: Replace the placeholder download buttons with actual App Store/Google Play links
2. **Analytics**: Add Google Analytics or other tracking
3. **Contact Form**: Add a contact form instead of just email
4. **Social Media**: Add social media links
5. **Privacy Policy**: Add a privacy policy page
6. **Terms of Service**: Add terms of service page

### To Add App Store Links:
Replace the download buttons in `index.html`:
```html
<a href="YOUR_APP_STORE_LINK" class="btn btn-primary btn-large">Download for iOS</a>
<a href="YOUR_GOOGLE_PLAY_LINK" class="btn btn-primary btn-large">Download for Android</a>
```

## 🐛 Troubleshooting

### Common Issues:

**Images not loading:**
- Make sure image files are in the `assets/` folder
- Check file names match exactly (case-sensitive)
- Verify file paths in HTML

**Styling not applied:**
- Check that `styles.css` is in the same directory as `index.html`
- Clear browser cache
- Check browser console for errors

**Mobile menu not working:**
- Ensure `script.js` is properly linked
- Check for JavaScript errors in browser console

## 📞 Support

For technical support with this landing page, contact: **cabbook-support@proton.me**

---

**Built with ❤️ for CabBook**

