source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby "2.7.1"


gem "autoprefixer-rails"

gem "bootsnap", require: false
gem "honeybadger"
gem "sqlite3"
gem "puma"
gem "rack-canonical-host"
gem "rails", "~> 6.0.0"
gem "recipient_interceptor"
gem "sassc-rails"
gem "skylight"
gem "sprockets", "< 4"
gem "title"
gem "tzinfo-data", platforms: [:mingw, :x64_mingw, :mswin, :jruby]
gem "webpacker"

group :development do
  gem "listen"
  gem "web-console"
end

group :development, :test do
  gem "awesome_print"
  gem "pry-byebug"
  gem "pry-rails"
end

group :test do
  gem "formulaic"
  gem "launchy"
  gem "timecop"
  gem "webmock"
end

gem "suspenders", group: [:development, :test]

gem 'rack-mini-profiler', require: false
gem 'oj'
gem 'high_voltage'
gem 'bourbon', '>= 6.0.0'
gem 'spring-commands-rspec', group: :development
gem 'rspec-rails', '~> 3.6', group: [:development, :test]
gem 'shoulda-matchers', group: :test
gem 'simplecov', require: false, group: [:test]
gem 'webdrivers', group: :test
gem 'simple_form'
gem 'bullet', group: [:development, :test]
gem 'factory_bot_rails', group: [:development, :test]
gem 'standard', group: :development
gem 'delayed_job_active_record'
gem 'inline_svg'
gem 'bundler-audit', '>= 0.7.0', require: false, group: [:development, :test]
group :development do
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'rack-timeout', group: :production