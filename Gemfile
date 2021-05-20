source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'rails', '~> 6.0.3', '>= 6.0.3.2'

gem 'sqlite3', '~> 1.4'

gem 'puma', '~> 4.3'

gem 'sass-rails', '>= 6'

gem 'webpacker', '~> 4.0'

gem 'turbolinks', '~> 5'

gem 'jbuilder', '~> 2.7'

gem 'bootsnap', '>= 1.4.2', require: false

gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'

#Do not use *= require in Sass or your other stylesheets will not be able to access the Bootstrap mixins or variables.

# Bootstrap JavaScript depends on jQuery. 

#If you're using Rails 5.1+, add the jquery-rails gem to your Gemfile: 
gem 'jquery-rails'

group :development, :test do
  
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
 
  gem 'webdrivers'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
