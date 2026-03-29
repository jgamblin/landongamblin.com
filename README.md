# landongamblin.com

Personal website for Landon Gamblin -- built with Jekyll and hosted on GitHub Pages.

[![GitHub Pages Deploy](https://github.com/jgamblin/landongamblin.com/actions/workflows/pages.yml/badge.svg)](https://github.com/jgamblin/landongamblin.com/actions/workflows/pages.yml)

## Local Development

### Prerequisites

- Ruby 3.x
- Bundler (`gem install bundler`)

### Setup

```bash
bundle install
bundle exec jekyll serve
```

Then visit [http://localhost:4000](http://localhost:4000).

## Project Structure

```
.
├── _config.yml        # Jekyll site configuration
├── _layouts/          # Page layout templates
├── _includes/         # Reusable HTML partials
├── assets/css/        # Custom stylesheets
├── index.md           # Homepage content
├── 404.md             # Custom 404 page
├── Gemfile            # Ruby dependencies
└── CNAME              # Custom domain config
```

## License

MIT -- see [LICENSE](LICENSE) for details.
