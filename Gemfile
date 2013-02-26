source 'https://rubygems.org'

gem 'rails', '4.0.0.beta1'


gem 'anjlab-bootstrap-rails', :require => 'bootstrap-rails'
gem "omniauth-facebook"
gem "koala"
gem 'devise'
gem 'execjs'
gem 'bundler'
gem 'uservoice-ruby'
gem 'newrelic_rpm'
gem 'stripe'
gem 'activeadmin'
gem "permanent_records"
gem 'therubyracer', :platform => :ruby

group :production do 
	gem 'pg'
end

group :development do
	gem 'sqlite3'
end

group :test, :development do
	gem "factory_girl_rails", :require => false
	gem "rspec-rails"
	gem "rspec_junit_formatter"
	gem "capybara"
	gem "guard-rspec"
	gem "simplecov"
	gem "database_cleaner"
	gem "faker"

end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
	gem 'sass-rails',   '~> 3.2.3'
	gem 'coffee-rails', '~> 3.2.1'
	gem 'uglifier', '>= 1.0.3'
end

