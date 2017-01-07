source 'https://rubygems.org'

gem 'rails', '~> 5.0.1'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'spring'
gem 'pg'
gem 'aws-sdk'
gem 'aws-sdk-rails'
gem 'heroku-stage'
gem 'recipient_interceptor'
gem 'delayed_job_active_record'
gem 'rails-i18n'
gem 'devise'
gem 'devise-i18n'
gem 'activeadmin', github: 'activeadmin'
gem 'inherited_resources', github: 'activeadmin/inherited_resources'
gem 'activeadmin_addons'
gem 'active_skin'
gem 'pundit'
gem 'versionist'
gem 'responders'
gem 'active_model_serializers', '~> 0.9.3'
gem 'simple_token_authentication', '~> 1.0'
gem 'rack-cors', '~> 0.4.0'
gem 'paperclip', '~> 4.3'

group :production do
  gem 'rails_stdout_logging'
  gem 'rack-timeout'
end

group :test do
  gem 'rspec_junit_formatter', '0.2.2'
  gem 'shoulda-matchers', require: false
end

group :development do
  gem 'annotate'
  gem 'letter_opener'
end

group :development, :test do
  gem 'dotenv-rails'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'guard-rspec', require: false
  gem 'rspec-nc', require: false
end

group :production, :development, :test do
  gem 'tzinfo-data'
end
