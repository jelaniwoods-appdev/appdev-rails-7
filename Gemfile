source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

gem "importmap-rails", "~> 1.1"

# AppDev Gems
# ===========
gem 'faker', '~> 3.1.0'
gem 'devise', '~> 4.8'

group :development, :test do
  gem "standard", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

group :development do
  gem 'annotate'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'pry-rails'
  gem 'rack-canonical-host'
  gem 'rails_db'
  gem 'rails-erd'
  gem 'rollbar'
  gem 'skylight'
  gem 'web_git', github: 'firstdraft/web_git'
end

