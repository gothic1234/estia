source 'https://rubygems.org'
source 'http://rubygems.org'

ruby '1.9.3'
gem  'rails', '3.2.13'
gem 'heroku'

gem 'bootstrap-sass'
# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

gem 'jquery-rails'

gem 'active_attr'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
  
  gem 'therubyracer'
  gem 'less-rails'
  gem 'twitter-bootstrap-rails'

end

group :development, :test do
  gem 'sqlite3'
  gem "rspec-rails"
end

group :production do
  gem 'pg'
  gem 'thin'
end

group :test do
  gem "factory_girl_rails"
  gem "capybara"
  gem "guard-rspec"
end

group :development do
  gem "growl"
  gem "growl_notify"
  gem "rb-fsevent"
end


# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'