# Aditya Aswani's Personal Website

A fast, modern personal website built with [Zola](https://www.getzola.org/) static site generator and the [Abridge](https://github.com/jieiku/abridge) theme.

## 🌐 Live Site

Visit: [adityaaswani.com](https://adityaaswani.com)

## 🛠️ Technology Stack

- **Static Site Generator**: [Zola](https://www.getzola.org/)
- **Theme**: [Abridge](https://github.com/jieiku/abridge) - A fast, lightweight theme
- **Styling**: Sass/SCSS with semantic HTML and minimal CSS
- **Performance**: Optimized for speed with no mandatory JavaScript
- **Features**: 
  - Search functionality (disabled by default)
  - Math rendering with KaTeX
  - Syntax highlighting support
  - PWA capabilities
  - Multi-language support
  - Dark/light theme toggle

## 📁 Project Structure

```
adityaaswani.com/
├── config.toml          # Main site configuration
├── content/             # Site content (Markdown files)
│   └── _index.md       # Homepage content
├── static/             # Static assets
├── sass/               # Custom Sass/SCSS files
│   ├── _extra.scss     # Custom styling
│   └── abridge.scss    # Theme base styles
├── templates/          # Custom page templates
├── themes/
│   └── abridge/        # Abridge theme files
└── public/             # Generated site output (auto-generated)
```

## 🚀 Getting Started

### Prerequisites

- [Zola](https://www.getzola.org/documentation/getting-started/installation/) installed

### Local Development

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd adityaaswani.com
   ```

2. **Serve the site locally**
   ```bash
   zola serve
   ```

3. **View the site**
   Open [http://127.0.0.1:1111](http://127.0.0.1:1111) in your browser

### Building for Production

```bash
zola build
```

The generated site will be in the `public/` directory.

## ⚙️ Configuration

### Site Settings

Edit `config.toml` to customize:

- **base_url**: Your domain (currently set to `https://adityaaswani.com/`)
- **title**: Site title (currently "Aditya Aswani")
- **theme**: Theme name (set to "abridge")

### Theme Customization

- **Sass/CSS**: Modify files in `sass/` directory
- **Templates**: Override theme templates in `templates/` directory
- **Static Files**: Add assets to `static/` directory

### Content Management

- Add pages in `content/` directory using Markdown
- Use front matter to configure page settings
- Organize content with sections and taxonomies

## 🎨 Theme Features

The Abridge theme provides:

- **Performance Optimized**: Fast loading with minimal JavaScript
- **Responsive Design**: Mobile-first approach
- **Accessibility**: Semantic HTML and ARIA support
- **Search**: Optional client-side search
- **Math Support**: KaTeX for mathematical expressions
- **Code Highlighting**: Syntax highlighting for code blocks
- **PWA Ready**: Progressive Web App capabilities
- **Multi-language**: Internationalization support

## 📝 Adding Content

### Creating a New Page

1. Create a new `.md` file in `content/`
2. Add front matter:
   ```toml
   +++
   title = "Page Title"
   date = 2024-01-01
   +++
   ```
3. Write your content in Markdown

### Creating a Blog Post

1. Create `content/blog/` directory if it doesn't exist
2. Add your post as `content/blog/post-title.md`
3. Include appropriate front matter

## 🔧 Development

### Custom Styling

Add custom CSS to `sass/_extra.scss`:

```scss
// Custom styles go here
```

### Theme Overrides

Override theme templates by copying from `themes/abridge/templates/` to `templates/` and modifying.

## 📦 Deployment

The site can be deployed to any static hosting service:

- **Netlify**: Connect your Git repository
- **Vercel**: Import your Git repository  
- **GitHub Pages**: Use GitHub Actions workflow
- **Traditional Hosting**: Upload `public/` directory contents

## 📄 License

This project uses the Abridge theme which is licensed under MIT. Check individual file licenses for specific components.

## 🤝 Contributing

This is a personal website, but suggestions and improvements are welcome via issues or pull requests.

## 📞 Contact

Visit [adityaaswani.com](https://adityaaswani.com) for contact information.