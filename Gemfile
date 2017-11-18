source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.6'
gem 'mysql2', '>= 0.3.18', '< 0.5'
#TODO:  unicorn + nginx
gem 'puma', '~> 3.0'

gem 'sass-rails', '~> 5.0'
gem 'haml-rails'
gem 'erb2haml'
gem 'autoprefixer-rails'

gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.5'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'jpmobile'
gem 'meta-tags'
gem 'breadcrumbs_on_rails'
gem 'draper'
gem 'kaminari', github: 'amatsuda/kaminari'
gem 'kakurenbo-puti' # https://github.com/alfa-jpn/kakurenbo-puti
gem 'react-rails'
gem 'marked-rails'

group :development, :test do
  gem 'hirb'
  gem 'hirb-unicode'
  gem 'pry'
  gem 'pry-rails'
  gem 'byebug', platform: :mri
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
