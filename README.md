# Kistarcsa Website

A simple, responsive website for Kistarcsa city, built with vanilla HTML, CSS, and JavaScript. Optimized for deployment on Vercel.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-friendly interface
- ⚡ Fast loading with optimized assets
- 🔒 Security headers configured
- 🌊 Smooth scrolling navigation
- ✨ CSS animations and transitions
- 🚀 Ready for Vercel deployment

## Project Structure

```
Kistarcsa-website/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with responsive design
├── script.js           # JavaScript for interactivity
├── vercel.json         # Vercel deployment configuration
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/foglalt/Kistarcsa-website.git
   cd Kistarcsa-website
   ```

2. Open `index.html` in your web browser, or serve it using a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. Visit `http://localhost:8000` in your browser.

## Deployment on Vercel

### Automatic Deployment (Recommended)

1. Push your code to a GitHub repository
2. Visit [Vercel](https://vercel.com) and sign up/login
3. Click "New Project" and import your GitHub repository
4. Vercel will automatically detect it's a static site and deploy it
5. Your site will be live at `https://your-project-name.vercel.app`

### Manual Deployment

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy from your project directory:
   ```bash
   vercel
   ```

3. Follow the prompts to complete deployment

## Configuration

The `vercel.json` file includes:
- Static file serving configuration
- Security headers (X-Content-Type-Options, X-Frame-Options, X-XSS-Protection)
- Cache headers for static assets
- Routing configuration

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).