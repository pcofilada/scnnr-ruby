# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem 'rake', '~> 10.0'

group :development do
  gem 'pry', '~> 0.10'
end

group :test do
  gem 'rspec', '~> 3.5'
  gem 'rspec_junit_formatter', '~> 0.3'
  gem 'rubocop', '~> 0.49.0'
  gem 'rubocop-junit-formatter', '~> 0.1'
  gem 'rubocop-rspec', '~> 1.15.0'
  gem 'webmock', '~> 3.0'
end

gemspec
