source 'http://rubygems.org'

gem 'rails', '3.0.6'


group :development do
  gem 'rspec-rails', '2.5.0'
	gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'
end

group :test do
  gem 'rspec', '2.5.0'
  gem 'webrat', '0.7.1'
  gem 'spork', '0.9.0.rc4'
end

group :production, :staging do
  gem "pg"
end