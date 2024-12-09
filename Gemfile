source "https://rubygems.org"

# Use the GitHub Pages gem to manage Jekyll and dependencies
gem "github-pages", group: :jekyll_plugins

# Additional plugins for Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6" # Adds RSS feed support
end

# Platform-specific gems for Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for file watching on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# Add GitHub Flavored Markdown (GFM) parser for kramdown
gem "kramdown-parser-gfm"

# Lock `http_parser.rb` gem to v0.6.x for JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
