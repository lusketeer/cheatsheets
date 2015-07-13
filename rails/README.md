# Rails Cheat$heets

### Gemfile

```ruby
gem 'backbone-on-rails'   # backbone, no need to say more
gem 'ejs'  # embedded javascript for backbone templates
gem 'marked-rails'   # markdown format for text
gem 'foundation-rails'  # foundation css framework
gem 'devise'  # quick user authentication
gem 'sidekiq'   # background process

group :production do
  gem 'newrelic_rpm'   # better error information for production environment
  gem 'pg'  # PostgreSQL, no need to explain
  gem 'puma'  # great server to handle concurrency on heroku
end

group :development, :test do

  gem 'spring'  # fast application preloading

  # debugging
  gem 'web-console'
  gem 'byebug'
  gem 'better_errors'
  gem 'binding_of_caller'

  gem 'pry-rails' # irb alternative
  gem 'faker'   # fake data
end

group :test do
  gem 'rspec'   # tests
  gem 'factory_girl_rails' # test fixtures
end

```
