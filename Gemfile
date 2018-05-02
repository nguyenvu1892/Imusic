source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "~> 5.1.6"
gem "sqlite3"
gem "puma", "~> 3.7"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "jbuilder", "~> 2.5"
gem "ratyrate"
gem "ransack"
gem "bcrypt"
gem "config"
gem "rails-i18n", "~> 5.1"
gem "i18n-js"
gem "jquery-rails", "~> 4.3", ">= 4.3.1"
gem "pry-rails", :group => :development
gem "bootstrap-sass", "~> 3.3.7"
gem "will_paginate"
gem "figaro"
gem "font-awesome-rails"
gem "paperclip", "~> 6.0.0"
gem "mini_magick", "4.7.0"
gem "bootstrap-will_paginate"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "capybara", "~> 2.13"
  gem "selenium-webdriver"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]