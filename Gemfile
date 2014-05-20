
source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.4'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# for Heroku i think
gem 'rails_12factor'
# not sure what this does
gem 'protected_attributes'
# for adding authentication
gem 'devise'
# to make forms prettier
gem 'simple_form', '~> 3.1.0.rc1', github: 'plataformatec/simple_form'
# Allows the uploading of images - make sure you have imagemagick installed on your local
gem 'carrierwave'
# For resizing of images
gem 'mini_magick', '~> 3.7.0'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.2'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# I succumbed into using this for quick design.....ugh
gem 'bootstrap-sass', '~> 3.1.1'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use postgresql as the database for Active Record
group :production do
	gem 'pg'
end

# debugging gems cos they're awesome:
group :development, :test do
  gem 'pry'
  gem 'pry-rails' 
  gem 'pry-debugger' 
  gem 'pry-stack_explorer' 
  gem 'better_errors' 
  gem 'annotate'
  gem 'rspec-rails'
  gem 'shoulda-matchers', '~> 2.6.1'
  gem 'factory_girl'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

