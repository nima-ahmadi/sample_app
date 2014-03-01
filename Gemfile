source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'
gem "bootstrap-sass", "~> 3.1.1.0"
gem "bcrypt-ruby", "~> 3.1.5"
gem "faker", "~> 1.2.0"
gem "will_paginate", "~> 3.0.5"
gem "bootstrap-will_paginate", "~> 0.0.10"
gem "jquery-rails", "~> 3.1.0"

group :development, :test do
	# Use sqlite3 as the database for Active Record
	gem 'sqlite3'
	gem "rspec-rails", "~> 2.14.1"
	gem "guard-rspec", "~> 4.2.7"
	gem "guard-spork", "~> 1.5.1"
	gem "childprocess", "~> 0.5.1"
	gem "spork", "~> 0.9.2"
end

group :assets do
	# Use SCSS for stylesheets
	gem 'sass-rails', '~> 4.0.0'

	# Use Uglifier as compressor for JavaScript assets
	gem 'uglifier', '>= 1.3.0'

	# Use CoffeeScript for .js.coffee assets and views
	gem 'coffee-rails', '~> 4.0.0'
end



group :test do
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
  # gem 'launchy', '2.1.0'
  # gem 'rb-fsevent', '0.9.1', :require => false
  # gem 'growl', '1.0.3'
end

group :production do
  gem 'pg'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
