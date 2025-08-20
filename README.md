# Aditya Aswani's Personal Website

A mindful digital space where meditation meets technology. This personal website showcases Aditya's projects, meditation teachings, and writings, built with [Zola](https://www.getzola.org/) static site generator and the [Abridge](https://github.com/jieiku/abridge) theme.

## 🌐 Live Site

Visit: [adityaaswani.com](https://adityaaswani.com)

## 🧘 About This Site

This website serves as a central hub connecting Aditya's various projects and offerings:

- **Meditation Guidance**: One-on-one meditation teaching on a donation basis
- **Projects**: Including Pause Pal (meditation accountability program) and Caliro (mindful Android OS)
- **Writings**: Links to personal blogs and essays
- **Contact**: Easy ways to get in touch

## 🛠️ Technology Stack

- **Static Site Generator**: [Zola](https://www.getzola.org/) (Rust-based)
- **Theme**: [Abridge](https://github.com/jieiku/abridge) - A fast, lightweight theme
- **Styling**: Sass/SCSS with semantic HTML and minimal CSS
- **Performance**: Optimized for speed with no mandatory JavaScript
- **Features**: 
  - Math rendering with KaTeX (enabled)
  - PWA capabilities
  - Dark/light theme toggle
  - Email encoding for privacy
  - Responsive design

## 📁 Project Structure

```
adityaaswani.com/
├── config.toml          # Main site configuration
├── content/             # Site content (Markdown files)
│   ├── _index.md       # Homepage content
│   ├── about.md        # About page with projects info
│   ├── contact.md      # Contact information
│   └── learn-meditation.md  # Meditation guidance page
├── static/             # Static assets (images, etc.)
├── sass/               # Custom Sass/SCSS files
│   ├── _extra.scss     # Custom styling
│   └── abridge.scss    # Theme base styles
├── templates/          # Custom page templates
│   ├── base.html       # Base template override
│   ├── home.html       # Homepage template
│   └── macros.html     # Template macros
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

Key configurations in `config.toml`:

- **base_url**: `https://adityaaswani.com/`
- **title**: "Aditya Aswani" 
- **description**: Focuses on software engineering and meditation
- **theme**: "abridge" - Fast, lightweight theme
- **email**: hello@adityaaswani.com (with encoding enabled)
- **Social links**: GitHub, LinkedIn, Twitter
- **PWA**: Enabled for app-like experience
- **KaTeX**: Enabled for mathematical expressions

### Theme Customization

- **Sass/CSS**: Modify files in `sass/` directory
- **Templates**: Override theme templates in `templates/` directory
- **Static Files**: Add assets to `static/` directory

### Content Management

Current pages:
- **Homepage** (`_index.md`): Hero section with personal intro
- **About** (`about.md`): Projects (Pause Pal, Caliro) and blog links
- **Contact** (`contact.md`): Email contact information
- **Learn Meditation** (`learn-meditation.md`): Meditation teaching services

## 🎨 Current Features

This site utilizes:

- **Performance Optimized**: Fast loading with minimal JavaScript
- **Responsive Design**: Mobile-first approach
- **Accessibility**: Semantic HTML and ARIA support
- **Math Support**: KaTeX enabled for mathematical expressions
- **PWA Ready**: Progressive Web App capabilities
- **Theme Toggle**: Dark/light mode switching
- **Email Protection**: Encoded email addresses

## 📝 Content Guidelines

### Page Structure

Each page includes:
- Front matter with title, description, date
- Template specification (page.html or home.html)
- Optional table of contents (currently disabled)

### Adding New Content

1. Create a new `.md` file in `content/`
2. Add front matter:
   ```toml
   +++
   title = "Page Title"
   description = "Brief description"
   date = 2024-01-01
   template = "page.html"
   +++
   ```
3. Write your content in Markdown

## 🔧 Development

### Custom Styling

Add custom CSS to `sass/_extra.scss`:

```scss
// Custom styles go here
```

### Theme Overrides

Override theme templates by copying from `themes/abridge/templates/` to `templates/` and modifying.

## 📦 Deployment

The site can be deployed to any static hosting service. After running `zola build`, upload the contents of the `public/` directory:

- **Netlify**: Connect your Git repository (recommended for auto-deployment)
- **Vercel**: Import your Git repository  
- **GitHub Pages**: Use GitHub Actions workflow
- **Traditional Hosting**: Upload `public/` directory contents

## 🎯 Site Purpose

This website reflects Aditya's unique intersection of technology and mindfulness:

- **Meditation Teaching**: Offering guidance rooted in Theravada Buddhist tradition
- **Mindful Technology**: Projects like Caliro focus on intentional device usage
- **Community Building**: Pause Pal connects meditation practitioners
- **Personal Expression**: A space for essays and regular updates

## 📄 License

This project uses the Abridge theme which is licensed under MIT. Check individual component licenses for specific details.

## 📞 Contact

For questions about the site or meditation guidance, visit the [contact page](https://adityaaswani.com/contact/) or email hello@adityaaswani.com.