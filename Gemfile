source 'https://rubygems.org'

gem 'rails', '~> 5.2.8', '>= 5.2.8.1'
gem 'rails-i18n', '>= 5.0.0'
if defined?(JRUBY_VERSION)
  gem 'jdbc-mysql', platform: :jruby
  gem 'activerecord-jdbc-adapter', '>= 52.0', platform: :jruby
else
  gem 'mysql2', '~> 0.3.21'
end
gem 'daemons-rails'
gem 'redis-rails'

gem 'rotp'
gem 'json', '>= 2.3.0'
gem 'jbuilder'
gem 'bcrypt-ruby', '~> 3.1.2'

gem 'doorkeeper', '~> 4.2.6'
gem 'omniauth', '~> 2.0.0'
gem 'omniauth-identity', '~> 2.0.0'

gem 'figaro'
gem 'hashie'

gem 'aasm', '~> 3.4.0'
gem 'amqp', '~> 1.3.0'
gem 'bunny', '~> 1.2.1'
gem 'cancancan'
gem 'enumerize', '~> 1.1', '>= 1.1.1'
gem 'datagrid'
gem 'acts-as-taggable-on'
gem 'kaminari', '>= 1.2.1'
gem 'paranoid2'
gem 'active_hash'
gem 'http_accept_language'
gem "globalize", "~> 5.2.0"
gem 'paper_trail', '~> 4.0.0'
gem 'rails-observers'
gem 'country_select', '~> 2.1.0'

gem 'gon', '~> 6.4.0'
gem 'pusher'
gem 'eventmachine', '~> 1.0.4'
gem 'em-websocket', '~> 0.5.1'

gem 'simple_form', '~> 5.0.0'
gem 'slim-rails'
gem 'sass-rails'
gem 'coffee-rails'
gem 'uglifier'
gem "jquery-rails", ">= 4.4.0"
gem "angularjs-rails"
gem 'bootstrap-sass', '~> 3.4.0.0'
gem 'bootstrap-wysihtml5-rails'
gem 'font-awesome-sass'
gem 'bourbon'
gem 'momentjs-rails'
gem 'eco'
gem 'browser', '~> 0.8.0'
gem 'liability-proof', '0.0.9'
gem 'whenever', '~> 0.9.2'
gem 'grape', '~> 1.1.0'
gem 'grape-entity', '~> 0.4.8'
gem 'grape-swagger', '~> 0.7.2'
gem 'rack-attack', '~> 4.3.1'
gem 'easy_table', '>= 0.0.8'
gem 'phonelib', '~> 0.3.5'
gem 'twilio-ruby', '~> 3.11'
gem 'unread', github: 'peatio/unread'
gem 'carrierwave', '~> 1.3.2'
gem 'simple_captcha2', '>= 0.3.0', require: 'simple_captcha'
gem 'rest-client', '~> 1.8.0'


group :development, :test do
  gem 'factory_girl_rails'
  gem 'faker', '~> 1.4.3'
  gem 'mina'
  gem 'mina-slack', github: 'peatio/mina-slack'
  gem 'meta_request', '>= 0.5.0'
  gem 'better_errors', '>= 2.8.0'
  # gem 'binding_of_caller'
  gem 'pry-rails'
  gem 'quiet_assets'
  gem 'mails_viewer'
  gem 'timecop'
  gem 'dotenv-rails', '>= 2.2.2'
  gem 'rspec-rails'
  unless defined?(JRUBY_VERSION)
    gem 'byebug'
    gem 'rbtree'
  else
    gem 'rbtree-jruby'
  end
end

group :test do
  gem 'database_cleaner'
  gem 'mocha', :require => false
  gem 'shoulda-matchers'
  gem 'capybara'
  gem 'launchy', '>= 2.4.3'
  gem 'selenium-webdriver'
  gem 'poltergeist'

  # rspec-rails rely on test-unit if rails version less then 4.1.0
  # but test-unit has been removed from ruby core since 2.2.0
  gem 'test-unit'
end

group :production do
  gem 'agent_fix'
end
