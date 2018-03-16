source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "jekyll-feed", "~> 0.6"
