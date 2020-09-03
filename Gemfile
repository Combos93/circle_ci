source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.1"

gem "rails", "6.0.3.1"

gem "pg", ">= 0.18", "< 2.0"

group :development, :test do
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "rspec-rails"
  gem "standard"
  gem "fasterer"
  gem "brakeman"
  gem "bundler-audit"
  gem "rubycritic"
end

group :test do
  gem "capybara"
  gem "simplecov", require: false
end

group :development do
  gem "annotate"
  gem "web-console", ">= 3.3.0"
end
