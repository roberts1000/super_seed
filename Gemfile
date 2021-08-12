source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in super_seed.gemspec
gemspec

group :development do
  gem 'rspec_starter', "~> 2.0", require: false
  gem 'rubocop_plus', "~> 2.0", require: false
end

group :development, :test do
  gem 'puma', '~> 5.4'
end
