source 'https://rubygems.org'

gem 'rails', '3.2.5'

# database
gem 'sqlite3'

group :assets do
  gem 'haml-rails'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'rspec-rails', '>= 2.10.1'
  gem 'factory_girl_rails', '>= 3.3.0'
  gem 'spork-rails'
  gem 'guard-rspec', '>= 1.2.1'
end

group :test do
  gem 'cucumber-rails',  '>= 1.3.0', require: false
  gem 'database_cleaner', '>= 0.7.2'
  gem 'capybara', '>= 1.1.2'
  gem 'rb-fchange', '0.0.5', :platforms => [:mswin, :mingw]
  gem 'rb-notifu', '0.0.4', :platforms => [:mswin, :mingw]
  gem 'win32console', :platforms => [:mswin, :mingw]

  group :linux do
    gem 'rb-inotify', '>= 0.8.8'
    gem 'libnotify', '>= 0.5.9'
  end

end

# frameworks
gem 'jquery-rails'

# styles
gem 'bootstrap-sass', '>= 2.0.3'

# authorization
gem 'devise', '>= 2.1.0'