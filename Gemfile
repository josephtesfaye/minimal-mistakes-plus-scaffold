source 'https://rubygems.org'

gem 'faraday-retry'
gem 'jekyll', '~> 3.9'
gem 'kramdown-parser-gfm'
gem 'minima', '~> 2.5'
gem 'minimal-mistakes-jekyll'
gem 'org-ruby'
gem 'webrick'

group :jekyll_plugins do
  gem 'jekyll-algolia'
  gem 'jekyll-feed'
  gem 'jekyll-gist'
  gem 'jekyll-include-cache'
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
  gem 'jemoji'
  gem 'minimal-mistakes-plus', github: 'josephtesfaye/minimal-mistakes-plus', branch: 'main'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '~> 1.2'
  gem 'tzinfo-data'
end

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1.1', :platforms => [:mingw, :x64_mingw, :mswin]
