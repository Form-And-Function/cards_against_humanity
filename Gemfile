# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby File.read('.ruby-version').chomp

gem 'aasm'
gem 'acts_as_list'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'bootstrap'
gem 'flipper'
gem 'flipper-redis'
gem 'flipper-ui'
gem 'jbuilder', '~> 2.10'
gem 'newrelic_rpm'
gem 'okcomputer'
gem 'pg', '>= 0.18', '< 2.0'
gem 'pg_query', '>= 0.9.0'
gem 'pghero'
gem 'puma', '~> 5.1'
gem 'rails', '~> 6.0.3'
gem 'redis'
gem 'rollbar'
gem 'sass-rails', '>= 6'
gem 'sidekiq'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 5.2'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'rubocop'
  gem 'rubocop-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.4'
  gem 'rails_real_favicon'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara'
  gem 'launchy'
  gem 'rspec_junit_formatter'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
