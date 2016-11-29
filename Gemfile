source 'https://rubygems.org'

require 'json'
require 'open-uri'

gem 'jekyll-admin', group: :jekyll_plugins

versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']