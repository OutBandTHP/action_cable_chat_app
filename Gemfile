source 'https://rubygems.org'

ruby '3.1.2'

gem 'rails',                   '7.2.2'
gem 'bcrypt',                  '3.1.13'
gem 'faker'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :development, :test do
  gem 'sqlite3', '2.6.0'                                       # instead of '1.3.13'
  gem 'byebug',  platform: :mri
  gem 'wdm', '>= 0.1.0' if Gem.win_platform?
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'rails-controller-testing'
  gem 'minitest-reporters'
  gem 'guard'
  gem 'guard-minitest'
end

group :production do
  gem 'pg',  '1.5.9', platforms: [:x64_mingw]                 # instread of '0.19.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]