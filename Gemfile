source 'https://rubygems.org'

gem 'jekyll', '~> 4.3.0'

# Core plugins for al-folio
group :jekyll_plugins do
    gem 'jekyll-archives-v2'  # Note: this is different from jekyll-archives
    gem 'jekyll-archives'     # Keep both versions for compatibility
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-imagemagick'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-toc'         # Required for {% toc %} tag in layouts
    gem 'jemoji'
end

# Development and build dependencies
gem 'csv'
gem 'ostruct'
gem 'observer'
gem 'base64'
gem 'webrick', '~> 1.8'
gem 'faraday-retry'

# Dependencies for plugins
gem 'feedjira' # Required by external-posts plugin
gem 'httparty' # Required by some plugins
gem 'css_parser' # Required by download-3rd-party plugin
gem 'bibtex-ruby' # Required by jekyll-scholar
gem 'latex-decode' # Required by jekyll-scholar
gem 'unicode_utils' # Required by some plugins

# For GitHub Pages compatibility, but not using github-pages gem
# to avoid version conflicts with Jekyll 4.x
