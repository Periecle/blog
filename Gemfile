# frozen_string_literal: true

source 'https://rubygems.org'

gem "jekyll-theme-chirpy", "~> 5.4", ">= 5.4.0"

group :jekyll_plugins do
  # If you have any plugins, put them here!
  # gem "jekyll-xxx", "~> x.y"
  gem "jekyll-sitemap"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ /mingw|mswin|java/ } do
  gem 'tzinfo', '~> 1.2'
  gem 'tzinfo-data'
end

gem "webrick", "~> 1.8"
