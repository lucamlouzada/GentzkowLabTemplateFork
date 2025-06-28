# Gentzkow Lab Practice Tasks Website

This is a Jekyll website built with the Just the Docs theme that converts the `task.md` file into a beautiful, navigable website similar to the [Econ RA Guide](https://raguide.github.io/).

## Features

- **Clean Navigation**: Sidebar navigation with collapsible sections
- **Search Functionality**: Full-text search across all pages
- **Responsive Design**: Works on desktop and mobile devices
- **Dark/Light Mode**: Toggle between color schemes
- **Anchor Links**: Direct links to specific sections
- **Mobile-Friendly**: Optimized for all screen sizes

## Local Development

### Prerequisites

1. **Install Ruby**: Make sure you have Ruby installed (version 2.6 or higher)
2. **Install Jekyll**: Install Jekyll and Bundler

```bash
gem install jekyll bundler
```

### Running Locally

1. **Install dependencies**:
   ```bash
   bundle install
   ```

2. **Start the development server**:
   ```bash
   bundle exec jekyll serve
   ```

3. **View the website**: Open your browser and go to `http://localhost:4000`

## Deployment

### GitHub Pages (Recommended)

1. **Push to GitHub**: Push this repository to GitHub
2. **Enable GitHub Pages**: 
   - Go to your repository settings
   - Scroll down to "GitHub Pages" section
   - Select "Deploy from a branch"
   - Choose the `main` branch and `/docs` folder
3. **Update _config.yml**: Change the `url` in `_config.yml` to match your GitHub Pages URL

### Alternative: Netlify

1. **Connect to Netlify**: Connect your GitHub repository to Netlify
2. **Build settings**:
   - Build command: `bundle exec jekyll build`
   - Publish directory: `_site`
3. **Deploy**: Netlify will automatically build and deploy your site

## File Structure

```
├── _config.yml          # Jekyll configuration
├── Gemfile              # Ruby dependencies
├── index.md             # Homepage
├── _tasks/              # Task pages
│   ├── index.md         # Tasks overview
│   ├── task1.md         # Task 1 content
│   ├── task2.md         # Task 2 content
│   └── task3.md         # Task 3 content
└── README_website.md    # This file
```

## Customization

### Theme Settings

Edit `_config.yml` to customize:
- Site title and description
- Color scheme (light/dark)
- Search functionality
- Footer content
- Navigation structure

### Adding New Pages

1. Create a new `.md` file in the appropriate directory
2. Add front matter with layout and navigation settings:
   ```yaml
   ---
   layout: default
   title: Your Page Title
   parent: Parent Section
   nav_order: 5
   ---
   ```

### Styling

The Just the Docs theme provides extensive customization options. See the [theme documentation](https://just-the-docs.github.io/just-the-docs/docs/configuration/) for more details.

## Troubleshooting

### Common Issues

1. **Bundle install fails**: Make sure you have the correct Ruby version
2. **Jekyll serve doesn't work**: Check that all dependencies are installed
3. **Pages not showing**: Verify the front matter is correct
4. **Navigation issues**: Check the `nav_order` and `parent` settings

### Getting Help

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Just the Docs Theme](https://just-the-docs.github.io/just-the-docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

## Contributing

To contribute to this website:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `bundle exec jekyll serve`
5. Submit a pull request

## License

This website is part of the Gentzkow Lab template and follows the same licensing terms. 