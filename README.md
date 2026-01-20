# Personal Website - CV, Publications & Social Media

This is a Jekyll-based GitHub Pages website showcasing my professional profile, curriculum vitae, scientific publications, and social media links.

## Features

- **Curriculum Vitae**: Education, professional experience, and skills
- **Publications**: List of scientific publications with links
- **Social Media**: Links to GitHub, LinkedIn, Twitter, ORCID, and Google Scholar
- **Responsive Design**: Mobile-friendly layout

## Setup Instructions

### Prerequisites

- Ruby (version 3.0 or higher)
- Bundler
- Jekyll

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/SaloM0nk/salom0nk.github.io.git
   cd salom0nk.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Customization

1. **Update personal information**: Edit `_config.yml` to add your name, email, and social media profiles
2. **Update CV content**: Edit `index.html` to update your education, experience, and skills
3. **Update publications**: Edit the publications section in `index.html` with your papers
4. **Customize styling**: Modify `assets/css/style.css` to change colors and layout

## Deployment

The site is automatically deployed to GitHub Pages using GitHub Actions when you push to the `main` branch.

To enable GitHub Pages:
1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select "GitHub Actions"

## Structure

```
.
├── _config.yml           # Site configuration
├── _layouts/
│   └── default.html      # Main layout template
├── _includes/
│   └── social-links.html # Social media links component
├── assets/
│   └── css/
│       └── style.css     # Site styling
├── index.html            # Main page with CV and publications
├── Gemfile               # Ruby dependencies
└── .github/
    └── workflows/
        └── jekyll.yml    # GitHub Actions workflow
```

## License

This project is open source and available under the MIT License.
