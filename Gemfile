source 'https://rubygems.org'

gem 'rails', '3.2.5'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# gem 'sqlite3'

# for Heroku, replace "gem 'sqlite3'" in your Gemfile with this:
group :development, :test do
  # if you already have a 'group :development,:test' block in your
  # Gemfile, you can just move the line "gem 'sqlite3'" into it.
  gem 'sqlite3' # 'mysql' # use SQLite only in development and testing
end 
group :production do
  gem 'pg' # use PostgreSQL in production (Heroku)
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'

# Code added as per ELLS on 6/9 
# Code commented as per https://class.coursera.org/saas-2012-002/forum/thread?thread_id=615
#  gem 'therubyracer'
# Code added as per https://class.coursera.org/saas-2012-002/forum/thread?thread_id=615
  gem 'execjs'
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

# Code added as per ELLS on 6/9 (http://pastebin.com/AGMAxaag)
# use Haml for templates
gem 'haml'
# use Ruby debugger
group :development, :test do
# Commented as per https://class.coursera.org/saas-2012-002/forum/thread?thread_id=615
#  gem 'ruby-debug19'
end