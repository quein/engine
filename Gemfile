# Edit this Gemfile to bundle your application's dependencies.
source 'http://rubygems.org'

gem 'rails', '3.0.0.rc'

gem 'liquid', '2.0.0'
# i think we'll need to fork our templating language
# gem 'locomotive-liquid'

gem 'bson_ext', '>= 1.0.1'
gem 'mongoid', :git => "git://github.com/durran/mongoid.git", :ref => "e387a0d1dc74da057472"
gem 'mongoid_acts_as_tree', '0.1.5'
gem 'mongo_session_store', '2.0.0.pre'
gem 'warden'
gem 'devise', :git => "git://github.com/plataformatec/devise.git"
gem 'haml', '3.0.15'
gem 'rmagick', '2.12.2'
gem 'aws'
gem 'mimetype-fu', :require => 'mimetype_fu'
gem 'formtastic-rails3', '1.0.0.beta3', :require => 'formtastic'
gem 'carrierwave', '0.5.0.beta2'
gem 'actionmailer-with-request', :require => 'actionmailer_with_request'
gem 'heroku'
gem 'httparty', '0.6.1'
gem 'RedCloth'
gem 'inherited_resources', '1.1.2'
gem 'jeweler'

# Development environment
group :development do
  # Using mongrel instead of webrick (default server)
  gem 'mongrel'
  gem 'cgi_multipart_eof_fix'
  gem 'fastthread'
end

group :test, :development do
  gem 'ruby-debug'
end

group :test do
  gem "autotest"
  gem "growl-glue"
  gem 'rspec-rails', '2.0.0.beta.19'
  gem 'factory_girl_rails'
  gem "pickle", :git => "http://github.com/codegram/pickle.git"
  gem "pickle-mongoid"
  gem 'capybara'

  # would be nice..
  # gem "capybara-envjs"

  gem 'database_cleaner'
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'spork'
  gem 'launchy'
  gem 'mocha', :git => 'git://github.com/floehopper/mocha.git'
end