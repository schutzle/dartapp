source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.1'
gem 'pg'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'haml-rails'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'draper'
gem 'sorcery'
gem 'font-awesome-rails'
gem 'bootstrap'
gem 'simple_form'
gem 'jquery-ui-rails'
gem 'chart-js-rails', git: 'https://github.com/teamairship/chart-js-rails.git'

group :development do
  gem 'binding_of_caller'
  gem 'pry'
  gem 'pry-byebug'
  gem 'better_errors'
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'i18n-tasks', '~> 0.9.8'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
