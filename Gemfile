source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.4'
gem 'puma', '~> 3.10.0'
gem 'sass-rails', '~> 5.0.6'
gem 'uglifier', '>= 3.2.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'devise', '~> 4.3'
#gem 'bcrypt-ruby', '3.1.5', :require => 'bcrypt'
#gem 'bcrypt', '~> 3.1', '>= 3.1.11'
#gem 'bcrypt', platforms: :ruby
gem "paperclip", '= 4.3.6'
gem 'aws-sdk-v1'#, '~> 3.0', '>= 3.0.1'
gem 'aws-sdk', '< 2.0'
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do
	gem 'sqlite3'	
end

group :production do
	gem 'pg', '0.21.0'
	gem 'rails_12factor', group: :production
end
