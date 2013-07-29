source 'http://rubygems.org'
source 'http://gemcutter.org'
source 'http://gems.github.com'

gem 'rails', '3.2.13'

gem 'acts_as_commentable', '3.0.1'
gem 'acts_as_paranoid', '~> 0.4.2'
gem 'acts_as_state_machine', :git => 'git://github.com/bikezilla/acts_as_state_machine.git'
gem 'acts_as_versioned', :git => 'git://github.com/pavel-so/acts_as_versioned.git'
gem 'american_date'
gem 'amatch'
gem 'barby'

# instead of vendor/plugins/super_inplace_controls
gem 'best_in_place', "~> 0.2.0"

gem 'bio'
gem 'carmen'
gem 'carmen-rails'
gem 'crypt'
gem 'delayed_job_active_record'

# IS: this isn't supported anymore
# consider using simple-form instead
gem 'dynamic_form'

gem 'exception_notification'

# IS: Should be installed automatically if therubyracer is installed
# gem 'execjs'

# IS: not sure, but we can avoid using this
# gem 'libv8', '~> 3.16.14.1'

# IS: obsolete if we're going to use Asset Pipeline
gem 'jammit'

# patched to open source file as binary, necessary in ruby 1.9
# IS: suggest removing -- is used only in app/models/attachment.rb:133
gem 'ezcrypto', '0.7.2', :path => "vendor/gems/ezcrypto-0.7.2"

gem 'google-spreadsheet-ruby'
gem 'gpgme', '~> 2.0.2'
gem 'haml'
gem 'hpricot'
gem 'jquery-rails'
gem 'memcache-client'
gem 'mimetype-fu', :require => 'mimetype_fu'
gem 'mysql2'
gem 'net-ldap', '0.2.2'
gem 'newrelic_rpm'
gem 'oauth2'
gem 'oink'
gem 'paperclip'
gem 'rack-oauth2', '~> 1.0.0'

# IS: don't think we need these
# gem 'rake', '0.9.2.2'

gem 'rb-inotify', '~> 0.9.0'

gem 'recaptcha', '0.2.3', :require => 'recaptcha/rails'
gem 'remotipart', "~> 1.0"
gem 'ri_cal'
gem 'rmagick'
gem 'roo'
gem 'rubyzip'
gem 'sanitize'
gem 'spreadsheet'
gem 'sunspot_rails'
gem 'thin'
gem 'timecop'
gem 'uuid'
gem 'whenever'
gem 'wicked_pdf'
gem 'will_paginate', '~> 3.0.4'
gem 'xmlcanonicalizer', '~> 0.1.1'
gem 'yfactorial-roxy', :require => 'roxy'

group :assets do
  # needed for deployment
  gem 'compass'
  gem 'compass-rails'

  gem 'sass-rails' #,   '~> 3.2.3'
  gem 'coffee-rails' #, '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>=1.0.3'
end

group :cucumber do
  gem 'factory_girl'
  gem 'database_cleaner'
  gem 'cucumber-rails'
  gem 'factory_girl_rails'
  #This is just to get the same version of rspec as in test.rb
  gem 'rspec-rails'
  gem 'capybara', '1.1.2'
  gem 'headless'
  gem 'pry'
  gem 'pry-remote'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
end

group :development do
  #Preformance analyzier gems we'll only need in dev
  #config.gem 'bullet' , :lib => false
  gem 'spork', '~> 1.0rc'
  gem 'spork-rails'
  gem 'guard-cucumber'
  gem 'guard-rspec'
  gem 'guard-coffeescript'
  gem 'guard-sass', :require => false
  gem 'capistrano', '~> 2.11.2'
  gem 'rails-dev-boost', :git => 'git://github.com/thedarkone/rails-dev-boost.git'
  gem 'pry'
  gem 'pry-remote'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
  gem 'cucumber-console'
  gem 'debugger'
  gem 'sunspot_solr'
end

group :test do
  gem 'oauth2'
  gem 'capybara' , '1.1.2'
  gem 'rspec-rails'
  gem 'rspec-retry'
  gem 'factory_girl'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'selenium'
  gem 'selenium-client' #, '~> 1.2.16'
  gem 'sunspot_test'
  gem 'sham'
  gem 'pry'
  gem 'pry-remote'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
  gem 'poltergeist'
  gem 'phantomjs', :require => 'phantomjs/poltergeist'
  gem 'guard-rspec'
  gem 'spork', '~> 1.0rc'
  gem 'guard-spork'
  gem 'launchy'
end
