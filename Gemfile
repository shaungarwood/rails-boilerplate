# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.1'

gem 'rails', '~> 7.0.4', '>= 7.0.4.3'
gem 'strong_migrations'
gem 'draper'

gem 'sprockets-rails'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'importmap-rails'
gem 'turbo-rails'
gem 'stimulus-rails'
gem 'jbuilder'
gem 'bootsnap', require: false

group :development, :test do
  gem 'pry'
  gem 'pry-byebug'
  gem 'dotenv-rails'
  gem 'factory_bot_rails', '~> 6.2'
  gem 'rspec-rails', '~> 6.0.0'
  gem 'rubocop', require: false
end

group :development do
  gem 'web-console'
  gem 'pry-rails'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
end
