source 'https://rubygems.org'
ruby '2.2.2'

gem 'haml' #gem used for enabling haml
gem 'protected_attributes' #added by pman
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
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
  gem 'sqlite3'
end

group :production do
#make sure the following gems are in your production group:
gem 'pg' #use PostgreSQL in production (Heroku)
gem 'rails_12factor' #Heroku-specific production settings
end
group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'rspec-rails'
  gem "erb2haml" #added by pman to convert existing erb to haml
  gem 'haml-rails' #added by pman to convert existing erb to haml
  gem "table_print"
end

group :test do
gem 'simplecov', :require => false
gem 'cucumber-rails',:require => false
gem 'cucumber-rails-training-wheels' #some pre-fabbed step definitions
gem 'database_cleaner' #to clear Cucumber's test databse between runs
gem 'capybara' #lets Cucumber pretend to be a web browser
gem 'launchy' #a usefule debuggin aid for user stories
gem 'guard-rspec'
gem 'cucumber-websteps'
end
