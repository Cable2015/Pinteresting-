source 'https://rubygems.org'
ruby '2.2.0'

gem 'rails', '4.2.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'bootstrap-sass'
gem 'devise', '~> 3.4.1.rc2'
gem "rack-offline"

group :development, :test do

	gem 'sqlite3'
end

group :production do
	gem 'pg'  # Postgres
	gem 'rails_12factor', group: :production
end

group :development, :test do

  # Call 'byebug' anywhere in the code to stop execution and get a dgit pusebugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  
end

