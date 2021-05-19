source 'https://rubygems.org'
ruby '2.6.3'

gem 'dotenv-rails' , '>= 2.2.1' # We want dotenv to load before everything else.

gem 'rails', '>= 5.0.6'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 5.0.6'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '>= 4.2.2'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.3.1'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'gitlab-turbolinks-classic', '>= 2.5.6'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc'

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring

gem 'puma'
gem 'devise', '>= 4.6.2'
gem 'omniauth'
gem 'paperclip'
gem 'aws-sdk', '< 3' # 2 is out but not compatible with paperclip
gem 'redcarpet'
gem 'simple_form', '>= 3.5.0'
gem 'foundation-rails', '5.5.3.2' #git: 'https://github.com/embersds/foundation-rails', branch: 'v5'
gem 'kaminari', '>= 1.0.1'
gem 'stripe'
gem 'redis'
gem 'sidekiq'
gem 'delayed_paperclip', '< 4'
# gem 'sinatra' # used for sidekiq ui
gem 'jwt'
gem 'font-awesome-rails', '>= 4.7.0.2', '< 5'
gem 'bundle-audit'
gem 'sentry-raven'

# City of Brass
gem 'activeplay', :path => 'engines/activeplay'
gem 'billing', :path => 'engines/billing'
gem 'campaignmanager', :path => 'engines/campaignmanager'
gem 'entitybuilder', :path => 'engines/entitybuilder'
gem 'gallery', :path => 'engines/gallery'
gem 'report', :path => 'engines/report'
gem 'rulebuilder', :path => 'engines/rulebuilder'
gem 'storybuilder', :path => 'engines/storybuilder'
gem 'support', :path => 'engines/support'
gem 'worldbuilder', :path => 'engines/worldbuilder'

group :development, :test do
  gem 'figaro'
  gem 'meta_request', '>= 0.4.3'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'foreman'
  gem 'get_process_mem'
  gem 'rails-controller-testing', '>= 1.0.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'listen', '~> 3.0.5'
end

group :production, :staging do
  gem 'rails_12factor'
  gem 'newrelic_rpm'
end
