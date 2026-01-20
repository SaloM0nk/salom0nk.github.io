# Personal Website - CV, Publications & Social Media

This is a Jekyll-based GitHub Pages website showcasing my professional profile, curriculum vitae, scientific publications, and social media links using the [Modern Resume Theme](https://github.com/sproogen/modern-resume-theme).

## Features

- **Modern Resume Theme**: Professional, responsive design optimized for resumes
- **Curriculum Vitae**: Education, professional experience, and skills
- **Publications**: List of scientific publications with links
- **Social Media**: Links to GitHub, LinkedIn, ORCID, and Google Scholar
- **Dark Mode Support**: Optional dark mode theme
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
2. **Update CV content**: Edit the `content` section in `_config.yml` to update your education, experience, and skills
3. **Update publications**: Edit the publications section in `_config.yml` with your papers
4. **Add profile image**: Add your profile image to `images/profile.jpg` and update the `about_profile_image` setting

For more information on customizing the theme, see the [Modern Resume Theme documentation](https://github.com/sproogen/modern-resume-theme).

## Deployment

The site is automatically deployed to GitHub Pages using GitHub Actions when you push to the `main` branch.

To enable GitHub Pages:
1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select "GitHub Actions"

## Structure

```
.
├── _config.yml           # Site configuration and all content
├── Gemfile               # Ruby dependencies
└── .github/
    └── workflows/
        └── jekyll.yml    # GitHub Actions workflow
```

## Theme

This site uses the [Modern Resume Theme](https://github.com/sproogen/modern-resume-theme) by [James Grant](https://github.com/sproogen).

## License

This project is open source and available under the MIT License.
