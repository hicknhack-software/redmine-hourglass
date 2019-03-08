source 'https://rubygems.org'

# asset pipeline
gem 'uglifier'
gem 'coffee-script', '~> 2.4.1'
gem 'sass', '~> 3.5.1'

gem 'rb-inotify', '<0.10', require: RUBY_PLATFORM.include?('linux') # required for ruby 2.0 support

# access control
gem 'pundit', '~> 1.1.0'

# this is useful for unix based systems which don't have a js runtime installed
# if you are on windows and this makes problems, simply remove the line
gem 'therubyracer', :platform => :ruby

# views
gem 'slim', '~> 3.0.8'
gem 'js-routes', '~> 1.3'
gem 'momentjs-rails', '>= 2.10.7'

gem 'rswag', '<2.0' # api docs
gem 'rspec-core'
gem 'rqrcode', '~> 0.10.1'

group :development, :test do
  gem 'rubycritic', '<4.0.0', require: false
  gem 'rainbow', '<3.0.0' # required for ruby 2.0 support
  gem 'rspec-rails', '~> 3.5', '>= 3.5.2'
  gem 'factory_bot_rails', '< 5.0'
  gem 'zonebie'
  gem 'timecop'
  gem 'faker', '1.7.3'
  gem 'database_cleaner'
end
