# Gemfile
source "https://rubygems.org"

# Use this if you're building your site with GitHub Actions
gem "jekyll", "~> 4.3.4"
gem "minima", "~> 2.5"

# Optional Jekyll themes
gem "jekyll-theme-hacker"
gem "jekyll-theme-cayman"
gem "jekyll-theme-midnight"
gem "aqua"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Platform-specific dependencies
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]
