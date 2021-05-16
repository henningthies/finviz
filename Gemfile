# frozen_string_literal: true

source "https://rubygems.org"

# Specify your gem's dependencies in finviz.gemspec
gemspec

gem "rake", "~> 13.0"

gem "pry", "~> 0.14.0"
gem "rubocop", "~> 1.14.0", require: false
gem "rubocop-rake", "~> 0.5.0", require: false
gem "rubocop-rspec", "~> 2.3.0", require: false

group :test do
  gem "rspec", ">= 3.10.0", "< 4.0"
  gem "rspec_junit_formatter"
  gem "vcr", "~> 6.0.0"
end
