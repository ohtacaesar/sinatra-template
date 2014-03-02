source 'https://rubygems.org'

gem 'rake'
gem 'sinatra', '~> 1.4.4', require: 'sinatra/base'
gem 'sinatra-contrib',     require: 'sinatra/contrib/all'
gem 'unicorn'

gem 'slim'
gem 'sass'

group :development, :test do
  gem 'rspec'
end

group :development do
  gem 'capistrano', '~> 3.1.0'
  gem 'capistrano3-unicorn', require: false

  gem 'rb-fsevent', '>= 0.9.3', require: false if RUBY_PLATFORM =~ /darwin/i
  gem 'guard'
  gem 'guard-rspec', require: false
end

