source 'https://rubygems.org'

ruby '~> 2.4'

gem 'rails', '~> 5.2.6'

gem 'sqlite3'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks', github: 'rails/turbolinks'
# Pin Puma to a recent-ish version that supports OpenSSL, which is
# what the CircleCI environment has.
gem 'puma', '~> 5.3'

group :test do
  gem 'capybara', '~>3.35'
  gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'percy-capybara', '~> 5.0.0'
end

group :production do
  gem 'rails_12factor'
end
