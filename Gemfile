# frozen_string_literal: true

source "https://rubygems.org"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  # gem "github-pages"
  # gem "jekyll-github-metadata"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.8"
gem "faraday-retry", "~> 2.2"

gem "jekyll-sass-converter", "~> 1.5"

gem "jekyll-paginate", "~> 1.1"

gem "jekyll-sitemap", "~> 1.4"

gem "kramdown-parser-gfm", "~> 1.1"
gem "kramdown", "~> 2.4"
gem "bundler", "~> 2.5"
gem "rake", "~> 13.1"
gem "appraisal", "~> 2.5"

gem "jekyll", "~> 3.9"
