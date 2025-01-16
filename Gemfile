source "https://rubygems.org"

# GitHub Pages gem ensures GitHub-compatible versions
gem "github-pages", "~> 231", group: :jekyll_plugins

gem "webrick", "~> 1.7"  # Only needed for local dev with Ruby 3.x

# Force a compatible version of Rouge if you prefer, or let github-pages handle it
# gem "rouge", "~> 3.30"

# Local dev plugins
group :jekyll_plugins do
  gem "jekyll-remote-theme"
  # No need to list feed, sitemap, etc., because github-pages already includes them.
end