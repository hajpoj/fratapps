source 'http://rubygems.org'

gem 'thin'

#use rails version 1.9.2p320 (if possible that's what I used to get it up and running)
gem 'rails', '~>3.0.20'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :production, :staging do
  gem "pg"
end

group :development, :test do
  gem "sqlite3-ruby", :require => "sqlite3"
end

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
group :development, :test do
  if RUBY_VERSION =~ /1.9/
    gem 'ruby-debug19'
  else
    gem 'ruby-debug'
  end
end
# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end
