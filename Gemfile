source 'https://rubygems.org'
ruby '2.1.0'

gem 'dalli'
gem 'acts-as-taggable-on'
gem 'airbrake'
gem 'bourbon'
gem 'choices'
gem 'daemons'
gem 'delayed_job'
gem 'delayed_job_active_record'
gem 'delayed_job_web'
gem 'devise'
gem 'devise-encryptable'
# NOTE: Newer versions of draper are currently incompatible with this codebase
gem 'draper', '< 0.13'
gem 'dynamic_form'
gem 'foreman'
gem 'sass-rails', '~> 4.0.0'
gem 'compass-rails', '~> 1.1.0'
gem 'bootstrap-sass'
gem 'pivotal-sass'
gem 'haml-rails'
gem 'jquery-rails'
gem 'mime-types'
gem 'nokogiri'
gem 'omniauth'
gem 'omniauth-google-oauth2'
gem 'pivotal-tracker', '0.5.8'
gem 'rails', '~> 4.0.0'
gem 'rake'
gem 'xpath'
gem 'whenever', :require => false
gem 'rails-backbone'
gem 'coffee-rails', '~> 4.0.0'
gem 'eco'
gem 'pg'
gem 'eventmachine'
gem 'em-http-request'
gem 'newrelic_rpm'
gem 'hashie'
gem 'unicorn'
# NOTE: this can be removed once we transition completely to Heroku
gem 'thin'
gem 'uglifier', '>= 1.3.0'

# work around for Google OpenID API change: https://github.com/sishen/omniauth-google-apps/issues/6
# can be removed once they fix
gem 'ruby-openid', :git => 'git://github.com/kendagriff/ruby-openid.git', :ref => '79beaa419d4754e787757f2545331509419e222e'

group :production do
  gem 'rails_12factor'
  gem 'therubyracer'
end

group :test do
  gem 'headless'
  gem 'vcr', '2.2.4'
  gem 'fakeweb'
  gem 'sqlite3'
end

# NOTE: anything that will not work in travis should be here
group :development do
  gem 'awesome_print'
  gem 'heroku_san'
  gem 'guard-livereload'
  gem 'rb-fsevent', '~> 0.9.1'
  gem 'ruby-prof'
end

group :test, :development do
  gem 'launchy'
  gem 'jshint_on_rails'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'capybara'
  gem 'jasmine', github: 'pivotal/jasmine-gem'
  gem 'jasmine-rails'
  # NOTE: selenium-webdriver >= 2.25.0 is needed for the latest Firefox
  gem 'selenium-webdriver', '>= 2.25.0'
  gem 'factory_girl_rails'
  gem 'ffaker'
  gem 'guard-coffeescript'
  gem 'database_cleaner'
  gem 'capybara-webkit'
  gem 'pry-nav'
  gem 'pry-rails'
  gem 'pry'
  gem 'vagrant'
  gem 'timecop'
end
