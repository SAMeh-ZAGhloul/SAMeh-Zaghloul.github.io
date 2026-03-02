# SAMeh-Zaghloul.github.io

Personal website for **Eng. Sameh Zaghloul** — CTIO & Enterprise Master IT Architect.

---

## Overview

A modern personal portfolio website showcasing 25+ years of enterprise architecture experience, expertise in AI, Blockchain, Cloud, Data, and Quantum Cryptography, along with 50+ completed projects and 60+ professional certifications.

**Built with:** Jekyll 4.4 • Responsive CSS • Semantic HTML

---

## Prerequisites

- **Ruby 3.2+** (required for Jekyll)
- **Bundler** (Ruby package manager)

### Install Ruby (macOS)

```bash
# Install or update Ruby via Homebrew
brew install ruby

# Update PATH to use Homebrew Ruby (add to ~/.zshrc)
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

# Verify installation
ruby -v  # Should show 3.2+
```

---

## Quick Start

### 1. Install Dependencies

```bash
bundle config set path 'vendor/bundle'
bundle install
```

### 2. Preview Locally

```bash
bundle exec jekyll serve --livereload
```

Then open **http://localhost:4000** in your browser.

### 3. Build for Production

```bash
bundle exec jekyll build
# Output generated in _site/ directory
```

---

## Editing Content

### Update Profile Content
Edit `index.md` to modify:
- Executive Summary
- Core Skills
- Experience & Roles
- Selected Projects
- Certifications & Recognition
- Gallery (images)

### Customize Layout & Styling
Edit `_layouts/default.html`:
- HTML structure
- CSS variables and styling
- Header, footer, navigation
- Responsive design rules

### Add/Replace Images
Place images in the `images/` folder, then reference in content as:
```markdown
![Alt text]({{ site.baseurl }}/images/filename.jpg)
```

### Site Configuration
Edit `_config.yml` to change:
- Site title, description, author
- Base URL and URL settings
- Theme and plugin preferences

---

## File Structure

```
.
├── _layouts/
│   └── default.html          # Main layout with header/footer/styles
├── _includes/                # Reusable HTML components (optional)
├── _posts/                   # Blog posts directory (optional)
├── assets/
│   ├── css/                  # Additional CSS files
│   └── js/                   # JavaScript files
├── images/                   # Profile photo, logos, diagrams
├── _config.yml               # Jekyll site configuration
├── Gemfile                   # Ruby dependencies
├── Gemfile.lock              # Dependency lock file
├── index.md                  # Home page content (front matter + markdown)
├── README.md                 # This file
└── .gitignore                # Git ignore rules
```

---

## Publishing to GitHub Pages

All changes pushed to the `main` branch are automatically deployed:

```bash
git add .
git commit -m "Update profile content"
git push origin main
```

GitHub Pages rebuilds and publishes your site within minutes.

---

## Troubleshooting

### Jekyll not found after Ruby update
```bash
gem install jekyll bundler
```

### Permission errors during bundle install
```bash
bundle config set path 'vendor/bundle'
bundle install
```

### Site not rebuilding on file changes
Restart the development server:
```bash
bundle exec jekyll serve --livereload
```

---

## Contact & Links

- **Email:** samah.saeed@fixed.global
- **LinkedIn:** https://www.linkedin.com/in/sameh-zaghloul-00b5151/
- **Digital Credentials:** https://www.youracclaim.com/user/sameh-zaghlou
- **Company:** Fixed Solutions Group

---

## License

© 2024 Eng. Sameh Zaghloul. All rights reserved.
