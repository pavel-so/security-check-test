source 'http://rubygems.org'
source 'http://gems.github.com'

# RAILS VER
gem 'rails', '3.2.17'

# obsolete / problematic
gem 'dynamic_form' # IS: this isn't supported anymore, consider using simple-form instead
gem 'jammit' # IS: obsolete if we're going to use Asset Pipeline
# patched to open source file as binary, necessary in ruby 1.9
# IS: suggest removing -- is used only in app/models/attachment.rb:133
gem 'ezcrypto', '0.7.2', :path => "vendor/gems/ezcrypto-0.7.2"

# hard versioned gems - please add a reason why it is hard versioned
gem 'acts_as_commentable', '3.0.1'
gem 'net-ldap', '0.2.2'

# lower version reqs
gem 'rubyzip', '< 1.0.0'

# loose versioned gems 
gem 'acts_as_paranoid', '~> 0.4.2'
gem 'ice_cube', '~> 0.11.0'
gem 'gpgme', '~> 2.0.2'
gem 'paperclip', '~> 3.5.2'
gem 'rack-oauth2', '~> 1.0.0'
gem 'rb-inotify', '~> 0.9.0' if /linux/ =~ RUBY_PLATFORM
gem 'remotipart', "~> 1.0"
gem 'will_paginate', '~> 3.0.4'
gem 'xmlcanonicalizer', '~> 0.1.1'

# github repo gems
gem 'acts_as_state_machine', :github => 'ilabsolutions/acts_as_state_machine'
gem 'acts_as_versioned', '3.2.2', :github => 'ilabsolutions/acts_as_versioned'
gem 'delayed_job_with_user', :github =>'ilabsolutions/delayed_job_with_user'
gem 'wicked_pdf', :git => 'git://github.com/mileszs/wicked_pdf.git'
gem 'respond_to_parent', github: 'Gonzih/respond_to_parent'

# no version specified
# system utils
gem 'delayed_job', github: "radiohead/delayed_job"
gem 'delayed_job_active_record'
gem 'daemons'
gem 'exception_notification'
gem 'haml'
gem 'hpricot'
gem 'jquery-rails'
gem 'memcache-client'
gem 'mysql2'
gem 'newrelic_rpm'
gem 'oauth2'
gem 'sunspot_rails'
gem 'crypt'
gem 'amatch'
gem 'rchardet', :require => false
gem 'xml-object', :require => false
gem 'rmagick'
gem 'sanitize'
gem 'timecop'
gem 'whenever'
gem 'uuid'
gem 'yfactorial-roxy', :require => 'roxy'
gem 'net-sftp'
gem 'guard-coffeescript'
gem 'guard-sass', :require => false

# UI / presentation utils
gem 'american_date'
gem 'barby'
gem 'best_in_place'
gem 'bio'
gem 'carmen'
gem 'carmen-rails'
gem 'recaptcha', :require => 'recaptcha/rails'
gem 'ri_cal'
gem 'google-spreadsheet-ruby'
gem 'roo'
gem 'spreadsheet'

# misc / unknown
gem 'mimetype-fu', :require => 'mimetype_fu'
gem 'oink'
gem 'progress_bar'

group :assets do
  gem 'compass'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>=1.0.3'
end

group :development, :test do
  gem 'pry'
  gem 'pry-remote'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
  gem 'pry-doc'
end

group :development do
  gem 'bullet', require: false
  gem 'annotate'
  gem 'capistrano', '~> 2.15.5'
  gem 'rails-dev-boost', :git => 'git://github.com/thedarkone/rails-dev-boost.git'
  gem 'thin'
  gem 'debugger'
  gem 'sunspot_solr'
  gem 'rubocop'
  gem 'better_errors'
end

group :test do
  gem 'perftools.rb', '~> 2.0.1', require: 'perftools', :git => 'git://github.com/tmm1/perftools.rb.git'
  gem 'sqlite3'
  gem 'capybara' , '1.1.2'
  gem 'rspec-rails'
  gem 'rspec-retry'
  gem 'factory_girl'
  gem 'factory_girl_rails'
  gem 'fuubar'
  gem 'database_cleaner', '~> 1.0.1'
  gem 'selenium'
  gem 'selenium-client' #, '~> 1.2.16'
  gem 'sunspot_test'
  gem 'sham'
  gem 'poltergeist'
  gem 'phantomjs', :require => 'phantomjs/poltergeist'
  gem 'launchy'
end
