source 'http://rubygems.org'

gem 'rails', '3.1.2'

group :development, :test do
  gem 'mysql2'
end

gem 'haml'
gem 'compass'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5.rc.2'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# For ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Server
# gem 'unicorn'

# Deployment
# gem 'capistrano'

gem 'heroku'


# Debugger
# gem 'ruby-debug19', :require => 'ruby-debug'


group :test do
  # Pretty printed test output
  gem 'turn', '~> 0.8.3', :require => false
  gem 'rspec'
end

group :production, :staging do
  gem 'pg'
end
