# Rails Cheat$heets

### Gemfile

```ruby
gem 'backbone-on-rails' # backbone, no need to say more
gem 'ejs' #embedded javascript for backbone templates
gem 'marked-rails' # markdown format for text
gem 'foundation-rails' # foundation css framework


group :production do
  gem 'newrelic_rpm'
  gem 'pg'
end

group :development do
  gem 'web-console'
  gem 'byebug'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry-rails'
end

group :test do
  gem 'faker'
end
```
