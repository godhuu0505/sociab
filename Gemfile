source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# rubyのフレームワーク
gem 'rails', '~> 5.1.4'
# DB
gem 'mysql2', '>= 0.3.18', '< 0.5'
# アプリケーションサーバ
gem 'puma', '~> 3.7'
# railsでsassを利用
gem 'sass-rails', '~> 5.0'
# bootstrap
gem 'bootstrap'
gem 'jquery-rails'
gem 'uglifier', '>= 1.3.0'
gem 'therubyracer', platforms: :ruby
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
# ログイン認証機能
gem 'devise'
# アクセス権限付与
gem 'cancancan'
# 管理画面
gem 'rails_admin'
# erb => haml 変換
gem 'erb2haml'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  # debug用
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-byebug'
  gem 'pry-stack_explorer'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
