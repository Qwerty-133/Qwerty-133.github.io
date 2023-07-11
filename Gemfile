source "https://rubygems.org"

gem 'dotenv-rails', groups: [:development, :test], require: 'dotenv/rails-now'

group :jekyll_plugins do
  gem "github-pages"
  gem 'jekyll-redirect-from'
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

# See https://github.com/jekyll/jekyll/issues/8523
gem "webrick", "~> 1.8"
