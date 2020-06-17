source "https://rubygems.org"

ruby "2.7.1"

gem "rails", ">= 5.0.0"
gem "jquery-rails", ">= 4.4.0"
gem "turbolinks"
gem "jbuilder"
gem "figaro"
gem "omniauth", ">= 1.9.1"
gem "omniauth-github", ">= 1.4.0"
gem "omniauth-google-oauth2", ">= 0.8.0"
gem "pg", "0.21" # to move to v1, must upgrade activesupport
gem "protected_attributes"
gem "state_machine_deuxito", require: 'state_machine'
gem "kaminari"
gem "actionpack-action_caching", ">= 1.2.0"
gem "rails_autolink", ">= 1.1.6"
gem "redcarpet"
gem "configurable_engine", ">= 0.5.0"
gem "bugsnag"
gem "stripe", "~> 3" # TODO upgrade this! Carefully...
gem "stripe_event"
gem "rack-canonical-host", ">= 0.2.3"
gem "aws-sdk-rails", ">= 2.1.0"
gem "rack-cors", ">= 1.0.6"
gem "haml-rails", ">= 1.0.0"
gem "sass-rails", ">= 5.0.7"
gem "uglifier"
gem "coffee-rails", ">= 4.2.2"
gem "bootstrap-sass"
gem "jquery-datatables-rails", ">= 3.4.0"
gem "bigdecimal", "1.4.4" # specify this directly to get around the error NoMethodError: undefined method `new' for BigDecimal:Class

group :development do
  gem "annotate" # Show db schema as comments in models
  gem "better_errors" , ">= 2.6.0" # Provides a better error page for Rails and other Rack apps
  gem "binding_of_caller" # Retrieve the binding of a method's caller
  gem "html2haml"
  gem "quiet_assets" , ">= 1.1.0" # turns off Rails asset pipeline log
  gem "awesome_print"
  gem "execjs" # last updated 2016
  gem "therubyracer" # Call JavaScript code and manipulate JavaScript objects from Ruby
end

group :development, :test do
  gem "rspec-rails", ">= 4.0.0"
  gem "thin", ">= 1.7.2"
  gem "faker"
  gem "rack_session_access", ">= 0.2.0"
  gem "pry-rails"
  gem "pry"
  gem "puma", "~>3" # TODO upgrading to 4 breaks the capybara tests- fix this
  gem "standard"
  gem "timecop"
end

group :production do
  gem "unicorn"
  gem "rails_12factor"
end

group :test do
  gem "capybara", ">= 3.32.1"
  gem "webdrivers"
  gem "database_cleaner"
  gem "email_spec"
  gem "factory_bot_rails", "~> 4", ">= 4.11.1"
  gem "launchy"
  gem "rspec-collection_matchers"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "stripe-ruby-mock", require: "stripe_mock"
  gem "simplecov"
end
