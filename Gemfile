# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "~> 5.1.6"
gem "mysql2", ">= 0.3.18", "< 0.6.0"
gem "puma", "~> 5.6"
gem "dotenv-rails"
gem "config"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "rubocop", require: false
gem "rubocop-rspec"
gem "slim-rails"
gem "seed-fu", "~> 2.3"
gem "draper"
gem "bootstrap-sass", "~> 3.4.1"
gem "sassc-rails", ">= 2.1.0"
gem "jquery-rails"
gem "popper_js", "~> 1.14.5"
gem "font-awesome-sass", "~> 5.8.1"
gem "ckeditor"
gem "carrierwave"
gem "mini_magick"
gem "coffee-rails", "~> 4.2"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "faker", "1.7.3"
gem "kaminari"
gem "bootstrap-kaminari-views"
gem "devise", "~> 4.1"
gem "ransack", git: "git://github.com/ernie/ransack.git"
gem "acts-as-taggable-on"
gem "impressionist"

group :development, :test do
  gem "capybara", "~> 2.13"
  gem "selenium-webdriver"
  gem "rspec-rails", "~> 3.8"
  gem "shoulda-matchers"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "pry-rails"
end

gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
