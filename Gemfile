# frozen_string_literal: true

source "http://rubygems.org"

gemspec

# Uncomment and change rails version for testing purposes
gem "rails", "~> 5.2.2"

group :development do
  gem "rubocop", "0.70.0", require: false
end

group :test do
  gem "coveralls", require: false
  gem "diffy"
  gem "equivalent-xml"
  gem "minitest"
  gem "sqlite3", "~> 1.3.6"
  gem "timecop"
end
