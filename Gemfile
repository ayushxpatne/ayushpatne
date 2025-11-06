# frozen_string_literal: true
source "https://rubygems.org"

# Specify the latest stable major version. Using `~> X.Y` allows Bundler to
# install any version greater than or equal to X.Y, but less than X.(Y+1).
# e.g., ~> 4.4 allows 4.4.0, 4.4.1, etc., but not 4.5.0.

gem "jekyll", "~> 3.9"

# Jekyll requires Webrick for serving the site locally, as it's no longer
# included in the standard Ruby library starting with Ruby 3.0.
gem "webrick", "~> 1.9"

# Use the optional group for plugins for better organization
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
end