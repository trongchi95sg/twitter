source 'https://rubygems.org'

ruby '2.2.5'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.2'
# Use mysql2 as the development database for Active Record
gem 'mysql2', '< 0.5'
gem 'transaction_retry' # fixes a deadlock bug in mysql
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# View stuff
gem "therubyracer"
gem "twitter-bootstrap-rails"
gem 'simple_form'
gem 'will_paginate'
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use puma as the app server
gem 'puma'

# queueing system
gem 'redis'
gem 'sidekiq'
gem 'sinatra'
gem 'whenever'

# managing workers
gem 'foreman'

# scraping
gem 'nokogiri'
gem 'httparty'
gem 'awesome_print'
gem 'savon'
gem 'geocoder'
gem 'countries', :require => 'countries/global'

# For formatting Puma proc titles and more!
gem 'rack-contrib'

# Affiliate Rewriting
gem 'affiliate_rewrite', '>= 0.3.9', git: 'git@git.dirox.net:nhuvt/affilicates_rewrite.git'

# Upload imports to s3
gem 'aws-sdk', '~> 2.0'

# Colorizing output of scraper review
gem 'colorize'

# Decompress zip file
gem 'rubyzip'

# Upload review to gist
gem 'gist'

# Monitoring
gem 'graphite-api'

# better wrapper class for attachments
gem 'mail'

# tourinfo
gem 'spreadsheet'
gem 'yomu'

# rake tasks
gem 'ruby-progressbar'
gem 'usagewatch'

group :development, :test, :staging do
  gem 'pry'
  gem 'factory_girl'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  gem 'shoulda-matchers', require: false

  gem 'rspec-rails'
  gem 'simplecov'

  gem 'database_cleaner'

  gem 'mutant-rspec'
end

group :development, :test do
  gem 'webmock'
end

# parse excel(.xlsx)
gem "roo"

# algoliasearch api
gem "algoliasearch"

# zipcode to city Japan
gem "zip_code_jp"
