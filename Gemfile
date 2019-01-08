source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.5.3"

gem "rails", "~> 5.2.2"

gem "bcrypt", "3.1.12"

gem "config"

gem "bootstrap-sass", "3.3.7"

gem "sqlite3"

gem "puma", "~> 3.11"

gem "sass-rails", "~> 5.0"

gem "uglifier", ">= 1.3.0"

gem "coffee-rails", "~> 4.2"

gem "turbolinks", "~> 5"

gem "jbuilder", "~> 2.5"

gem "rubocop", "~> 0.54.0", require: false

gem "bootsnap", ">= 1.1.0", require: false

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "chromedriver-helper"
  gem "guard", "2.13.0"
  gem "guard-minitest", "2.4.4"
  gem "minitest", "5.11.3"
  gem "minitest-reporters", "1.1.14"
  gem "rails-controller-testing", "1.0.2"
  gem "selenium-webdriver"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
