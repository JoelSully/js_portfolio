source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.0"
gem "rails", "~> 7.0.3", ">= 7.0.3.1"
gem "sprockets-rails"
gem "pg"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
    gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
    gem "web-console"
end

group :production do
    gem 'pg'
end

group :test do
    gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
