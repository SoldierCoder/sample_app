source 'https://rubygems.org'
ruby "2.1.2"

gem 'rails',        '4.2.2'
gem 'sass-rails',   '5.0.2'
gem 'uglifier',     '2.5.3'
gem 'coffee-rails', '4.1.0'
gem 'therubyracer', platforms: :ruby

gem 'jquery-rails', '4.0.3'
gem 'turbolinks',   '2.3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder',     '2.2.3'
gem 'sdoc',         '0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'sqlite3',    '1.3.9'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug',     '3.4.0'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  gem 'spring',     '1.1.3'

end

group :test do
  gem 'minitest-reporters', '1.0.5'
  gem 'mini_backtrace',     '0.1.3'
  gem 'guard-minitest',     '2.3.1'
end

group :production do 
  gem 'pg',                 '0.17.1'
  gem 'rails_12factor',     '0.0.2'
end