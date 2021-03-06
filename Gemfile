source 'https://rubygems.org'

ruby '2.1.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'
# Use sqlite3 or pg as the database for Active Record
gem 'sqlite3'
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
gem 'compass-rails', '~> 2.0.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
gem 'unicorn'
gem 'rack-timeout'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Loads environment variables from `.env`
gem 'dotenv-rails', :groups => [:development, :test]

# Handle settings by rails-settings-cached
gem 'rails-settings-cached', '0.4.1'

# Add Slim support
gem 'slim-rails'

gem 'friendly_id', '~> 5.0.4'
gem 'babosa'
gem 'ruby-pinyin'

gem 'devise', '~> 3.4.0'
gem 'cancancan', '~> 1.9.2'
gem 'omniauth-facebook', '~> 2.0.0'
gem 'doorkeeper', '~> 2.0.1'
gem 'httparty', '~> 0.13.1'

gem 'simple_form', '~> 3.1.0'

gem 'mailgunner', '~> 2.0.0'
gem 'nexmo'

# Make SEO-friendly meta tags and titles using meta-tags
gem 'meta-tags', '~> 2.0.0'

# Use activerecord-import to support bulk inserting data using ActiveRecord
gem 'activerecord-import', '~> 0.7.0'

# Use ActiveAdmin as the administration framework
gem 'activeadmin', github: 'activeadmin'

# Integrate swagger docs
gem 'swagger-docs', '~> 0.1.8'
gem 'swagger-ui_rails', '~> 0.1.7'

# Development tools
group :development do
  gem 'rails-erd'
  gem 'railroady'
  gem 'byebug'
  gem 'better_errors', '~> 2.1.0'
  gem 'binding_of_caller', '~> 0.7.2'
  gem 'meta_request'
  gem 'letter_opener'
  # gem 'guard-livereload', require: false
  # gem 'growl_notify', require: false
end

# RSpec
group :development, :test do
  gem 'rspec-rails', '~> 3.0'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'shoulda-matchers', require: false
  gem 'rspec-its', require: false
  gem 'simplecov', '~> 0.9.1', require: false
  gem 'coveralls', require: false
  gem 'capybara-webkit', '>= 1.2.0'
  gem 'database_cleaner'
  gem 'formulaic'
  gem 'launchy'
  gem 'webmock'
  gem 'timecop'
  gem 'faker'
end

# Follow the rules of 12Factor
gem 'rails_12factor', group: :production

# Logger and Monitoring Tools
gem 'remote_syslog_logger'
gem 'newrelic_rpm'

# Use Pry as the Rails console
gem 'pry-rails'
gem 'pry-byebug'
gem 'awesome_print', :require => false
gem 'hirb', :require => false
gem 'hirb-unicode', :require => false

# Assets related Gems
gem 'normalize-rails', '>= 3.0.1'
gem 'modernizr-rails'
# gem 'react-rails', '~> 1.0.0.pre', github: 'reactjs/react-rails'
gem 'nprogress-rails', '~> 0.1.6.4'
gem 'select2-rails', '~> 3.5.9'
