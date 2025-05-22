source 'https://rubygems.org'

gem 'github-pages', group: :jekyll_plugins

if ENV['JEKYLL_ENV'] == 'development'
    # Use local theme for testing
    gem 'jekyll-theme-ss-nes', path: '../jekyll-theme-ss-nes'
else
    # Use custom theme from GitHub repository
    gem 'jekyll-theme-ss-nes', git: 'https://github.com/SS-NES/jekyll-theme-ss-nes.git'
end
