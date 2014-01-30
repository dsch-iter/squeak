source 'https://rubygems.org'

gem 'rails', '3.2.7'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
gem 'debugger' unless ENV["RM_INFO"]

#START:focus
group :test do
  gem 'cucumber-rails', '1.3.0'
  gem 'rspec-rails', '2.11.0'
  gem 'database_cleaner', '0.8.0'
  gem 'factory_girl', '3.5.0'
  gem 'selenium-webdriver'
  #gem 'ruby-debug19', :require => 'ruby-debug'
  gem 'linecache19', '>= 0.5.13' #, :git => 'https://github.com/robmathews/linecache19-0.5.13.git'
  gem 'ruby-debug-base19x', '>= 0.11.30.pre10'
  gem 'ruby-debug-ide', '>= 0.4.17.beta14'
end
#END:focus
