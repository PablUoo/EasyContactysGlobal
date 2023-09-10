source 'https://rubygems.org'

gem 'rails_12factor', group: :production

# Use Puma as the app server

gem 'rails',                        '~> 5.0.5'
gem 'pg',                           '~> 0.18'
gem 'puma', 						'~> 4.3'
gem 'sass-rails',                   '~> 5.0'
gem 'uglifier',                     '>= 1.3.0'
gem 'coffee-rails',                 '~> 4.2'
gem 'jquery-rails',                 '4.2.1'
gem 'turbolinks',                   '~> 5'
gem 'bcrypt',                       '~> 3.1.7'
gem 'bootstrap-sass',               '3.4.1'
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
ruby '2.6.8'

gem "dockerfile-rails", ">= 1.5", :group => :development

gem "sentry-ruby", "~> 5.11"

gem "sentry-rails", "~> 5.11"
