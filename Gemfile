source 'https://rubygems.org'

gem 'rails', '3.2.13'

group :development, :test do
	gem 'mysql2'
	gem 'rspec-rails'
	gem 'guard-rspec', '1.2.1'
  gem 'bootstrap-sass', '2.1'
  gem 'bcrypt-ruby', '3.0.1'
  gem 'faker', '1.0.1'
  gem 'will_paginate', '3.0.3'
  gem 'bootstrap-will_paginate', '0.0.6'

  gem 'guard-spork', :github => 'guard/guard-spork' 
  gem 'spork', '0.9.2'
  gem 'childprocess'
end

group :development do
  gem 'annotate', '2.5.0'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :test do
  gem 'capybara', '1.1.2'
  gem 'rb-inotify', '0.8.8'
  gem 'libnotify', '0.5.9'
  gem 'factory_girl_rails', '4.1.0'
end

group :production do
  gem 'pg'
end
