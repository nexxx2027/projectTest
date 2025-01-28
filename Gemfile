source "https://rubygems.org"

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.4.1"

gem "rails", "~> 8.0.1"
gem "propshaft"
gem "sassc-rails", "2.1.2"
gem "sprockets-rails", "3.4.2"
gem "puma", ">= 5.6.4"
gem "importmap-rails", "~> 1.1.0"
gem "turbo-rails", "~> 1.1.1"
gem "stimulus-rails", "~> 1.0.4"
gem "jbuilder", "~> 2.11.5"
gem "bootsnap", "~> 1.18.4", require: false

gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "kamal", require: false
gem "thruster", require: false

# Uncomment if needed
gem "image_processing", "~> 1.2"

group :development, :test do
  gem "sqlite3", ">= 2.1"
  gem "debug", "~> 1.5.0", platforms: %i[ mri mingw x64_mingw ]
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console", "~> 4.2.0"
end

group :test do
  gem "capybara", "~> 3.37.1"
  gem "selenium-webdriver", "~> 4.2.0"
  gem "webdrivers", "~> 5.0.0"
end

group :production do
  gem "pg"
end
