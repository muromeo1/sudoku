source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.1'

gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.2', '>= 7.0.2.3'
gem 'sprockets-rails'
gem 'sqlite3', '~> 1.4'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'reek'
  gem 'rubocop'
end
