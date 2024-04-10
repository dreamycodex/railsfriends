source "https://rubygems.org"

ruby "3.3.0"


gem "rails", "~> 7.1.3", ">= 7.1.3.2"
gem "sprockets-rails"

gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console"
  gem "sqlite3", "~> 1.4"
end

group :production do
  gem 'pg', '~> 1.5', '>= 1.5.6'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
