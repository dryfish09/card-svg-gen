# Gemfile for GitHub Pages

source "https://rubygems.org"

# GitHub Pages gem - includes all required dependencies
gem "github-pages", group: :jekyll_plugins

# Required for Ruby 3.0+
gem "webrick", "~> 1.8"

# Windows compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
