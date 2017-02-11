source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
gem 'active_model_serializers', '~> 0.8.3' # NOTE: not the 0.9
gem 'devise'
gem "sqlite3", :platform => [:ruby, :mswin, :mingw]

gem 'thin'
gem 'listen'
group :development, :test do
  gem 'faker'
  gem 'byebug'
  gem 'spring'
end
gem 'web-console', group: :development
gem 'rack-cors', :require => 'rack/cors'