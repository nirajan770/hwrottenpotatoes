source 'http://rubygems.org'

gem 'rails', '3.2.14'
gem 'rake', '~>10.1.1'
# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'debugger'
end

group :production do
  gem 'pg'
   gem 'therubyracer' 
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
              
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'haml'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'
