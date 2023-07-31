source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.6"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Centralization of locale data collection for Ruby on Rails [https://rubygems.org/gems/rails-i18n]
gem 'rails-i18n', '~> 7.0', '>= 7.0.7'

# A flexible authentication solution for Rails [https://rubygems.org/gems/devise]
gem 'devise', '~> 4.9', '>= 4.9.2'

# Provides higher-level image processing helpers that are commonly needed when handling image uploads [https://rubygems.org/gems/image_processing]
gem 'image_processing', '~> 1.12', '>= 1.12.2'

# Add simple validations
gem 'active_storage_validations', '~> 1.0', '>= 1.0.4'

# Provides integration between factory_bot and rails [https://rubygems.org/gems/factory_bot_rails]
gem 'factory_bot_rails', '~> 6.2'

# A runtime developer console [https://rubygems.org/gems/pry/versions/0.14.1]
gem 'pry', '~> 0.14.1'

# A Ruby code style checking [https://rubygems.org/gems/rubocop]
gem 'rubocop', '~> 1.54', '>= 1.54.2'

# A library for generating fake data [https://rubygems.org/gems/faker]
gem 'faker', '~> 3.2'

# Code coverage for Ruby with a powerful configuration library and automatic merging of coverage across test suites [https://rubygems.org/gems/simplecov]
gem 'simplecov', '~> 0.22.0'

# Extracting `assigns` and `assert_template` from ActionDispatch [https://rubygems.org/gems/rails-controller-testing]
gem 'rails-controller-testing', '~> 1.0', '>= 1.0.5'

# A debugging tool for Ruby on Rails applications [https://rubygems.org/gems/web-console/versions/3.3.1]
gem 'web-console', '~> 3.3', '>= 3.3.1'

# Code style checking for RSpec files [https://rubygems.org/gems/rubocop-rspec/versions/2.22.0]
gem 'rubocop-rspec', '~> 2.22'

# Strategies for cleaning databases [https://rubygems.org/gems/database_cleaner/versions/1.5.3]
gem 'database_cleaner', '~> 1.5', '>= 1.5.3'

# Automatic Rails code style checking tool [https://rubygems.org/gems/rubocop-rails/versions/2.20.2]
gem 'rubocop-rails', '~> 2.20', '>= 2.20.2'





group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Run Selenium tests more easily [https://rubygems.org/gems/webdrivers/versions/3.2.0]
  gem 'webdrivers', '~> 3.2'
end