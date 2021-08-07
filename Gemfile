source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in super_seed.gemspec
gemspec

group :development do
  gem 'rubocop_plus', "~> 2.0", require: false
  gem 'rspec_starter', "~> 1.1", require: false
end

group :development, :test do
  gem 'puma', '~> 3.7'
end
