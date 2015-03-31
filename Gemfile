source 'https://rubygems.org'

gem 'rails', '3.2.19'
gem 'jquery-rails'
gem "unicorn", ">= 4.3.1"
gem "pg", ">= 0.14.1"
gem "haml", ">= 3.1.7"
gem "sendgrid", ">= 1.0.1"
gem "devise", ">= 2.1.2"
gem 'cancancan', '~> 1.9'
gem "simple_form", ">= 2.0.4"
gem 'turnout'
gem 'daemons'
gem 'figaro'
gem 'mini_portile', '0.6.2'

gem "friendly_id"
gem "delayed_job_active_record", "0.4.1"
gem 'bootstrap-sass', '~> 3.0.3.0'
gem 'delayed-plugins-airbrake' # notify airbrake on exception
gem "airbrake", '~> 4.1.0'
gem "rabl"
gem "kaminari"
gem "andand"
gem "dj_mon"
gem 'braintree-rails'
gem 'carmen-rails' # required by braintree rails
gem "whenever", require: false
gem "prawn", require: false
gem "paperclip", "~> 3.4.2"
gem 'aws-sdk-v1', "~> 1.62.0"
gem 'aws-sdk', "2.0.24", require: false
gem 'money-rails'
gem 'hashie'
gem 'doorkeeper', '~> 0.6.7'
gem 'json_select'
gem 'squeel' # extends AREL
gem 'with_advisory_lock'
gem 'secure_headers'

gem "wysiwyg_docs" , github: "safesoftware/wysiwyg_docs", branch: 'master'
gem 'bootstrap-wysihtml5-rails'
gem 'css_splitter'
gem 'rufus-scheduler', require: false
gem 'dante', require: false
gem 'erubis', require: false
gem 'json'
gem 'git'
gem 'scout_api'
gem 'compass-rails'
gem 'slack-notifier'

# used for reserved instance time calculations
gem 'time_diff'

# Librato Adapter
gem 'rest-client'

# Ip Lookup
gem 'geocoder'

# Google Authenticator
gem 'devise_google_authenticator', github: "safesoftware/devise_google_authenticator", branch: "feature/recovery_codes"

# OAuth
gem "omniauth-google-oauth2"

# Strong param (remove when we move to rails 4)
gem 'strong_parameters'

# logging activity
gem "public_activity"

gem 'state_machine'

# Salesforce integration
gem 'databasedotcom', '>= 1.3.2'

# CORS
gem 'rack-cors', require: 'rack/cors'

gem 'appsignal'
gem 'pagerduty'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem "sass_rails_patch", "~> 0.0.1"
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem "compass-rgbapng", require: "rgbapng"
  # gem 'turbo-sprockets-rails3'
  gem "fog", "~>1.20", require: "fog/aws/storage"
  gem "asset_sync"
  gem "therubyracer"
end

group :test do
  gem "email_spec", ">= 1.2.1"
  gem "cucumber-rails", ">= 1.4.1", require: false
  gem "database_cleaner", ">= 0.9.1"
  gem "launchy", ">= 2.1.2"
  gem "capybara", ">= 2.1.0"
  gem "capybara-webkit"
  # gem "poltergeist"
  gem "selenium-webdriver", ">= 2.45.0"
  gem "machinist", ">= 2.0"
  gem "rspec-rails", ">= 2.11.0"
  gem "faker"
  gem "rspec_candy"
  gem 'webmock', "= 1.09"
  gem 'vcr'
  gem 'shoulda', :require => false
  gem 'json_spec'
  gem 'test_after_commit'
  gem 'timecop'
end

group :development do
  gem "haml-rails", ">= 0.3.5"
  gem "hpricot", ">= 0.8.6"
  gem "ruby_parser", ">= 2.3.1"
  gem "quiet_assets", ">= 1.0.1"
  gem 'guard-livereload'
  gem 'guard-zeus'
  # For model diagram generation
  gem 'rails-erd'
  # Opsworks deploy
  gem 'opsworks-deploy', github: "safesoftware/opsworks-deploy", branch: 'master' # path: '../opsworks-deploy'
  # Opsworks SSH
  gem 'opsworks-connect', github: "safesoftware/opsworks-connect", branch: 'master' # path: '../opsworks-connect'
end


group :test, :development do
  #debugging
  gem 'debugger', ">= 1.6.2"
  gem 'debugger-xml', ">= 0.3.2"
  # end debugging
  gem 'pry-rails'
  gem 'pry-debugger'
  gem 'pdf-inspector'
end

group :test, :cucumber do
  gem 'puma', require: false
  gem 'headless'
  gem 'zeus'
  gem 'fake_braintree', require: false
end

group :test, :cucumber, :development do
  gem "parallel_tests"
  gem 'zeus-parallel_tests'
end
