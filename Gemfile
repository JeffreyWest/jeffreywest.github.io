# frozen_string_literal: true

source "https://rubygems.org"
gemspec

# gem "jekyll", "~> 3.7.3"

gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate", "~> 1.1.0"
end

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end

source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
