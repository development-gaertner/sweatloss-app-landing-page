# Sweatloss Landing Page

Landing page for **Sweatloss**, a hydration tracking iOS app that helps users stay healthy by monitoring their daily water intake.

## About Sweatloss

Sweatloss is a privacy-focused, free hydration tracking app that makes it effortless to log your water intake and maintain healthy hydration habits. All your data stays on your device—no account required.

**Key Features:**

- Daily water tracking with quick logging
- Personalized hydration goals
- Progress insights with beautiful charts
- Multiple beverage tracking
- Privacy-focused (local data storage)
- HealthKit integration
- iCloud sync (optional)

## Technologies

This landing page is built with:

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting
- **SCSS** - Styling
- **Liquid** - Templating

## Landing Page Features

- App Store-style layout with screenshot gallery
- Responsive design optimized for all devices
- App information and download links in header
- Privacy policy page
- Changelog/What's New page
- Custom domain support

## Live Site

🌐 [sweatloss.app](https://sweatloss.app)

## Local Development

To run this site locally:

```bash
# Install Jekyll and dependencies
bundle install

# Run local server
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000) in your browser.

## Custom Domain Configuration

This repository is configured to use the custom domain `sweatloss.app` via GitHub Pages.

**DNS Configuration:**
The domain must be configured with A records pointing to GitHub Pages IPs:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

**GitHub Pages Settings:**

1. Go to repository Settings → Pages
2. Verify custom domain is set to `sweatloss.app`
3. Enable "Enforce HTTPS" (after DNS propagates)

## Credits

This landing page is based on the [Automatic App Landing Page](https://github.com/emilbaehr/automatic-app-landing-page) template by [Emil Baehr](https://emilbaehr.com/).

## License

[MIT License](LICENSE)
