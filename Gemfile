source 'https://rubygems.org'

gem 'jekyll'

gem 'logger', '~> 1.7'
gem 'base64', '~> 0.2.0'
gem 'bigdecimal', '~> 3.1', '>= 3.1.9'
gem 'kramdown-parser-gfm'

group :jekyll_plugins do
    gem 'jekyll-sitemap', '~> 1.4'
    gem 'jekyll-seo-tag', '~> 2.8'
end


# Use custom theme from GitHub repository
gem 'jekyll-remote-theme', '~> 0.4.3'

if ENV['JEKYLL_ENV'] == 'development'
    # Use local theme for testing
    gem 'jekyll-theme-ss-nes', path: '../jekyll-theme-ss-nes'
end
