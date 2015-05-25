# Do More

### Make a few more text files and work with `cat`

`$touch test_1.txt test_2.txt test_3.txt`

`$cat ex12.txt ex13.txt test_1.txt test_2.txt test_3.txt`

### Try `cat ex12.txt ex13.txt`

Hi there this is cool.
I am a fun guy.
Don't you know why?
Because I make poems,
that make babies cry.

# Alternative "english" ways of asking for your working directory

### Can you show me the contents of database.yml?

Yes by running the following command:

`$cat database.yml`

 SQLite version 3.x
   gem install sqlite3

   Ensure the SQLite 3 gem is defined in your Gemfile
   gem 'sqlite3'

default: &default
  adapter: sqlite3
  pool: 5
  timeout: 5000

development:
  <<: *default
  database: db/development.sqlite3

 Warning: The database defined as "test" will be erased and
 re-generated from your development database when you run "rake".
 Do not set this db to the same as development or production.
test:
  <<: *default
  database: db/test.sqlite3

production:
  <<: *default
  database: db/production.sqlite3

### What is in your Gemfile?

The `Gemfile` is where the specfic list of gems that are to be used.

`$cat Gemfile`

source 'https://rubygems.org'


 Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
 Use sqlite3 as the database for Active Record
gem 'sqlite3'
 Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
 Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
 Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
 See https://github.com/rails/execjs#readme for more supported runtimes
 gem 'therubyracer', platforms: :ruby

 Use jquery as the JavaScript library
gem 'jquery-rails'
 Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
 Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
 bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

 Use ActiveModel has_secure_password
 gem 'bcrypt', '~> 3.1.7'

 Use Unicorn as the app server
 gem 'unicorn'

 Use Capistrano for deployment
 gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
