source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.1'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
# gem 'therubyracer', platforms: :rubnstall mongoidy
# Use jquery as the JavaScript library

gem 'mongoid', '~> 6.0.0'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
group :test do
  gem "rspec-rails", '~> 3.5'
  gem 'rspec-activemodel-mocks'
  gem "database_cleaner"
  gem "shoulda-matchers"
  gem 'json_spec'
  gem "rspec-collection_matchers"
  gem 'capybara'
  gem 'rails-controller-testing'
  gem 'simplecov', require: false
end


group :development, :test do
  gem 'byebug', platform: :mri
  gem "factory_girl_rails"
  gem "ffaker", require: true
  gem 'rubocop', require: false
  gem 'dotenv-rails'
  gem 'capistrano', '3.6.1'
  gem 'webrick'
  gem 'quiet_assets'
  gem 'spring', '1.3.6'
  gem 'guard-rspec', require: false
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
