source 'https://rubygems.org'

gem 'rails', '~> 5.0.0'
gem 'rails-i18n', '>= 5.0.0'
if defined?(JRUBY_VERSION)
  gem 'jdbc-mysql', platform: :jruby
  gem 'activerecord-jdbc-adapter', platform: :jruby
else
  gem 'mysql2', '~> 0.3.21'
end
gem 'daemons-rails'
gem 'redis-rails'

gem 'rotp'
gem 'json'
gem 'jbuilder'
gem 'bcrypt-ruby', '~> 3.1.2'

gem 'doorkeeper', '~> 2.0.0'
gem 'omniauth', '~> 1.3.1'
gem 'omniauth-identity', '~> 2.0.0'

gem 'figaro'
gem 'hashie'

gem 'aasm', '~> 3.4.0'
gem 'amqp', '~> 1.3.0'
gem 'bunny', '~> 1.2.1'
gem 'cancancan'
gem 'enumerize', '~> 1.0'
gem 'datagrid', '>= 1.5.5'
gem 'acts-as-taggable-on'
gem 'kaminari', '>= 1.0.0'
gem 'paranoid2'
gem 'active_hash'
gem 'http_accept_language'
gem "globalize", "~> 4.0.0"
gem 'paper_trail', '~> 3.0.1'
gem 'rails-observers'
gem 'country_select', '~> 2.1.0'

gem 'gon', '~> 6.0.1'
gem 'pusher'
gem 'eventmachine', '~> 1.0.4'
gem 'em-websocket', '~> 0.5.1'

gem 'simple_form', '~> 3.2.1'
gem 'slim-rails', '>= 3.1.3'
gem 'sass-rails', '>= 5.0.7'
gem 'coffee-rails', '>= 5.0.0'
gem 'uglifier'
gem "jquery-rails", ">= 4.0.1"
gem "angularjs-rails"
gem 'bootstrap-sass', '~> 3.2.0.2'
gem 'bootstrap-wysihtml5-rails'
gem 'font-awesome-sass'
gem 'bourbon'
gem 'momentjs-rails', '>= 2.20.1'
gem 'eco'
gem 'browser', '~> 0.8.0'
gem 'liability-proof', '0.0.9'
gem 'whenever', '~> 0.9.2'
gem 'grape', '~> 0.8.0'
gem 'grape-entity', '~> 0.4.2'
gem 'grape-swagger', '~> 0.8.0'
gem 'rack-attack', '~> 4.0.0'
gem 'easy_table', '>= 0.0.8'
gem 'phonelib', '~> 0.3.5'
gem 'twilio-ruby', '~> 3.11'
gem 'unread', github: 'peatio/unread'
gem 'carrierwave', '~> 0.10.0'
gem 'simple_captcha2', '>= 0.3.0', require: 'simple_captcha'
gem 'rest-client', '~> 1.6.8'


group :development, :test do
  gem 'factory_girl_rails', '>= 4.9.0'
  gem 'faker', '~> 1.4.3'
  gem 'mina'
  gem 'mina-slack', github: 'peatio/mina-slack'
  gem 'meta_request', '>= 0.5.0'
  gem 'better_errors', '>= 2.4.0'
  # gem 'binding_of_caller'
  gem 'pry-rails'
  gem 'quiet_assets'
  gem 'mails_viewer', '>= 0.2.0'
  gem 'timecop'
  gem 'dotenv-rails', '>= 2.2.2'
  gem 'rspec-rails', '>= 3.7.0'
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
  gem 'capybara', '>= 2.15.2'
  gem 'launchy'
  gem 'selenium-webdriver'
  gem 'poltergeist', '>= 1.17.0'

  # rspec-rails rely on test-unit if rails version less then 4.1.0
  # but test-unit has been removed from ruby core since 2.2.0
  gem 'test-unit'
end

group :production do
  gem 'agent_fix'
end
