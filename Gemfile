# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "jekyll-theme-chirpy", "~> 7.4"
gem "jekyll-include-cache"
gem "jekyll-sitemap"
gem "jekyll-seo-tag"
gem "jekyll-paginate"
gem "jekyll-feed"

# For Chirpy compatibility
gem "webrick"

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

group :test do
  gem "html-proofer", "~> 5.0"
end
