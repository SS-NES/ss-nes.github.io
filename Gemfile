source 'https://rubygems.org'

gem 'logger', '~> 1.7'
gem 'base64', '~> 0.2.0'
gem 'bigdecimal', '~> 3.1', '>= 3.1.9'
gem 'kramdown-parser-gfm'

# Use custom theme from GitHub repository
gem 'jekyll-remote-theme', '~> 0.4.3'

if ENV['JEKYLL_ENV'] == 'development'
    # Use local theme for testing
    gem 'jekyll-theme-ss-nes', path: '../jekyll-theme-ss-nes'
else
    # Use published theme for GitHub Pages
    #
    # Note: currently disabled in favor of local theme for testing,
    # or GitHub hosted remote SS-NES theme.
    #
    # Uncomment the line below to use the RubyGems.org published theme
    # gem 'jekyll-theme-ss-nes', '~> 0.1.0'
end
