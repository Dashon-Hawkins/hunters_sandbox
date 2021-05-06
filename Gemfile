source 'https://rubygems.org'
ruby "2.2.3"

#use Postgres
gem 'pg'

gem 'devise', '>= 4.4.2'

gem 'puma'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.2.4.6'

gem "paperclip", "~> 4.3"
gem 'aws-sdk'
gem 'aws-sdk-v1'


# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0', '>= 5.0.5'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.0.4'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '>= 2.5.3'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem "rspec-rails", ">= 3.5.0"
  gem "factory_girl_rails", ">= 4.5.0"
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.2', '>= 2.2.1'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'pry'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :production do
  gem 'rails_12factor'
end

# This is the latest Bundler syntax for specifying custom
# sources. If you get an error with this just remove the
# block do and end
#
# Also this source is https, but if your machine has out of
# date SSL certs you might get SSL warnings from Ruby. In that
# case just fall back to http, which will still work.
source 'http://dresssed.com/gems/a32d5c5588e50352351a/' do
  gem 'dresssed-gimlet'
end

