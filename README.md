# Artizio Website

A Hugo-powered website for Artizio, an innovative coloring book app that transforms your photos into beautiful coloring pages.

## About Artizio

Artizio is a mobile application that allows users to:
- Transform photos into coloring book pages
- Create personalized coloring experiences
- Print and share their artwork
- Enjoy a creative and relaxing activity

## 🚀 Quick Start

### Prerequisites

- [Hugo](https://gohugo.io/getting-started/installing/) (extended version recommended)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:
```bash
git clone git@github.com:Ribicube/artizio-site.git
cd artizio-site
```

2. Initialize the theme submodule:
```bash
git submodule update --init --recursive
```

3. Start the development server:
```bash
hugo server -D
```

4. Open your browser and navigate to `http://localhost:1313`

## 📁 Project Structure

```
artizio-site/
├── content/           # Markdown content files
│   ├── _index.md     # Homepage content
│   ├── policy.md     # Privacy policy
│   └── terms.md      # Terms of service
├── layouts/          # Custom HTML templates
│   └── partials/     # Reusable template components
├── static/           # Static assets
│   ├── css/          # Custom stylesheets
│   └── images/       # Images and screenshots
├── themes/ananke/    # Hugo theme (git submodule)
├── hugo.toml         # Hugo configuration
└── README.md         # This file
```

## 🛠️ Development

### Adding Content

1. Create new content files in the `content/` directory
2. Use Hugo's front matter format (YAML, TOML, or JSON)
3. Write content in Markdown

### Customizing Styles

- Edit `static/css/custom.css` for custom styling
- The site uses the Ananke theme as a base

### Adding Images

- Place images in `static/images/`
- Reference them in content with `/images/filename.jpg`

## 🔧 Configuration

The site configuration is in `hugo.toml`. Key settings include:

- `baseURL`: Your site's base URL
- `title`: Site title
- `theme`: Currently using "ananke"
- `languageCode`: Site language

## 📱 App Screenshots

The repository includes screenshots of the Artizio mobile app in:
- `static/images/screenshots/` - App interface screenshots
- `static/images/logo/` - App logos and branding

## 🚢 Deployment

### Build for Production

```bash
hugo --minify
```

This generates static files in the `public/` directory.

### Deployment Options

- **GitHub Pages**: Enable GitHub Pages in repository settings
- **Netlify**: Connect your repository for automatic deployments
- **Vercel**: Deploy directly from GitHub
- **Traditional hosting**: Upload `public/` directory contents

## 🎨 Theme

This site uses the [Ananke theme](https://themes.gohugo.io/themes/gohugo-theme-ananke/) which provides:
- Responsive design
- Clean, modern layout
- SEO optimization
- Social media integration

## 📄 Content Pages

- **Homepage** (`content/_index.md`): Main landing page
- **Privacy Policy** (`content/policy.md`): Privacy policy
- **Terms of Service** (`content/terms.md`): Terms and conditions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Support

For questions about the website or the Artizio app, please contact [support@artizio.com](mailto:support@artizio.com).

## 📜 License

TODO

## 🔗 Links

- **Live Site**: [artizio.app](https://artizio.app/)
- [Artizio App Store](https://apps.apple.com/app/artizio) (Update with actual link)
- [Google Play Store](https://play.google.com/store/apps/details?id=com.artizio) (Update with actual link)
- [Hugo Documentation](https://gohugo.io/documentation/)
- [Ananke Theme Documentation](https://github.com/theNewDynamic/gohugo-theme-ananke)

---

Made with ❤️ for the Artizio community 