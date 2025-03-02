# RackTracker Website

This is a simple one-page promotional website for the RackTracker iOS app. The website is designed to be static and serve as a landing page for potential users to learn about the app and download it from the App Store.

## Structure

- `index.html` - The main HTML file for the website
- `css/styles.css` - Stylesheet for the website
- `images/` - Directory containing app screenshots, app icon, and favicon

## Required Images

For the website to display correctly, you need to add the following images to the `images/` directory:

1. `app-icon.png` - The RackTracker app icon (recommended size: 512x512px)
2. `favicon.png` - A small version of the app icon for browser tabs (recommended size: 32x32px)
3. `screenshot-1.png` - Screenshot of the Gear List View
4. `screenshot-2.png` - Screenshot of the Gear Detail View
5. `screenshot-3.png` - Screenshot of the Rack Management View
6. `screenshot-4.png` - Screenshot of the Climb Logging View

## Deployment Instructions

### Local Testing

To test the website locally, simply open the `index.html` file in a web browser.

### Hosting Options

#### Option 1: GitHub Pages (Free)

1. Create a GitHub repository for the website
2. Push the website files to the repository
3. Enable GitHub Pages in the repository settings
4. The website will be available at `https://[username].github.io/[repository-name]`

#### Option 2: Netlify (Free)

1. Create an account on [Netlify](https://www.netlify.com/)
2. Drag and drop the website folder to Netlify's upload area
3. The website will be deployed with a Netlify subdomain
4. You can configure a custom domain in the Netlify settings

#### Option 3: Custom Domain Hosting

1. Purchase a domain (e.g., racktracker.app)
2. Sign up for a web hosting service
3. Upload the website files to the hosting service via FTP
4. Configure the domain to point to the hosting service

## Customization

### App Store Link

Before deployment, update the App Store link in the `index.html` file:

```html
<a href="https://apps.apple.com/app/idXXXXXXXXXX" class="cta-button"><i class="fab fa-apple"></i> Download on App Store</a>
```

Replace `idXXXXXXXXXX` with your actual App Store ID once the app is published.

### Privacy Policy and Terms of Service Links

Update the links to your Privacy Policy and Terms of Service in the footer:

```html
<a href="privacy-policy.html">Privacy Policy</a> |
<a href="terms-of-service.html">Terms of Service</a>
```

You can either create these as separate HTML files or link to the relevant sections in the App Store listing.

## Maintenance

This is a static website, so it requires minimal maintenance. Update the screenshots and information as needed when new versions of the app are released. 