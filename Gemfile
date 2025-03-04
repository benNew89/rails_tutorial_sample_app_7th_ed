source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails",                      '7.0.4'

gem "image_processing",           '1.12.2'
gem "active_storage_validations", '0.9.8'
gem "bcrypt",                     '3.1.18'
gem "faker",                      '2.21.0'
gem "will_paginate",              '3.3.1'
gem "bootstrap-will_paginate",    '1.0.0'
gem "bootstrap-sass",             '3.4.1'
gem "sassc-rails",                '2.1.2'
gem "sprockets-rails",            '3.4.2'
gem "importmap-rails",            '1.1.0'
gem "turbo-rails",                '1.1.1'
gem "stimulus-rails",             '1.0.4'
gem "jbuilder",                   '2.11.5'
gem "puma",                       '>= 6.4.0'
gem "bootsnap",                   '1.12.0', require: false

gem 'sassc'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'redcarpet'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'que', '0.12.0'
gem 'postmark' #, '~> 1.15'
gem 'postmark-rails' #, '= 0.20'
gem 'sib-api-v3-sdk'
gem 'factory_bot_rails'
gem 'acts_as_list', '0.8.2'
gem 'mailerlite', '>= 1.0.5'
gem 'counter_culture', '~> 3.2'
gem 'ruby-progressbar'
gem 'sentry-ruby', '= 4.8.1'
gem 'sentry-rails', '= 4.8.1'
gem 'sentry-sidekiq', '= 4.8.1'

gem 'device_detector', git: 'https://github.com/podigee/device_detector'
gem 'm3u8'

gem 'mediainfo', git: 'https://github.com/jshow/mediainfo', :branch => 'protect_from_dashes_in_instance_names'
gem 'exifr'

gem 'omniauth-facebook', git: 'https://github.com/mkdynamic/omniauth-facebook'
gem 'rubyzip', '~> 2.3.0'

gem 'hiredis'
gem 'mixpanel-ruby', git: 'https://github.com/LifeTales/mixpanel-ruby', :branch => 'fix_event_import'

gem 'dry-types'
gem 'dry-struct'

gem 'prawn'
gem 'prawn-markup'

gem 'prawn-table'

gem 'rgeo', '= 2.4.0'

gem 'ffi', '= 1.16.3'

gem 'mini_portile2', '~> 2.8.0'

gem 'lograge'
gem 'logstash-event' # required for json log output from lograge

gem 'openssl'

gem "rqrcode", "~> 2.0"

gem 'thwait'

gem 'rmagick', '>= 4.2'
gem 'mini_magick'
gem 'ruby-vips'

gem 'mustache', '~> 1.0'

gem 'after_commit_everywhere'

gem 'slack-notifier'

gem 'zaru'

gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby', tag: 'v5.55.0'
gem 'stripe_event', git: 'https://github.com/integrallis/stripe_event', tag: 'v2.7.0'

# Active admin gems
#gem 'activeadmin', git: 'https://github.com/LifeTales/activeadmin', branch: '5669-add-ajaxed-pagination_upgrade_activeadmin'
gem 'activeadmin', git: 'https://github.com/LifeTales/activeadmin', branch: 'add-ajaxed-pagination_upgrade_activeadmin_upgrade_3.2.4'
gem 'devise'
gem 'devise-two-factor', '~> 6.0.o'
gem 'chartkick', '~> 4.1.2'
gem 'activeadmin_addons'

gem 'bootstrap', '~> 4.3.1'

gem 'enum_attributes_validation'

gem 'groupdate'

gem 'semantic'

gem 'rswag', '~> 2.5'
gem 'rspec-rails'



gem 'nokogiri', '>= 1.12.0'
gem 'loofah', '~> 2.21.2'

gem 'slim-rails'

gem 'anthropic'

gem 'tilt', '~> 2.2'

gem 'IPinfo'

gem 'time_ago_in_words'

gem 'coupon_code'

gem 'validates_email_format_of'

gem 'active_model_serializers', '~> 0.10.0'
gem 'activerecord-import'
gem 'pg', '1.3.5'
gem 'puma', '>= 6.4.0'
gem 'rack-attack', group: :production

group :development, :test do
  gem 'dotenv-rails', '~> 2.1', '>= 2.1.1'
  gem "sqlite3", "1.4.2"
  gem "debug",   "1.5.0", platforms: %i[ mri mingw x64_mingw ]
  gem 'rack-test'
  gem 'ed25519', ">= 1.2", "< 2.0"
  gem 'bcrypt_pbkdf', ">= 1.0", "< 2.0"
  gem 'byebug', platform: :mri
  gem 'json-schema'
  gem 'rb-inotify', '= 0.10.1'
  gem 'guard', '2.18.0', require: false
  gem 'guard-rspec', require: false
  gem 'guard-rake', require: false
  gem 'guard-livereload', require: false
  gem 'terminal-notifier'
  gem 'terminal-notifier-guard', require: false
  gem 'rails-erd'
  gem 'rails-controller-testing', "1.0.5"
  gem 'shoulda-matchers', git: 'https://github.com/thoughtbot/shoulda-matchers'
  gem 'timecop'
  gem 'n_plus_one_control'
  gem 'stripe-ruby-mock', :require => 'stripe_mock', tag: '3.1.0.rc3', git: 'https://github.com/stripe-ruby-mock/stripe-ruby-mock'
  gem 'rspec-translation', '~> 1.0', git: 'https://github.com/jshow/rspec-translation', branch: 'fix_to_work_with_ruby_3_0'
  gem 'rspec-json_expectations'
end

group :development do
  gem "web-console", "4.2.0"
  gem 'capistrano', '~> 3.10', require: false
  gem 'capistrano-rails', '~> 1.3', require: false
  gem 'capistrano-sidekiq'
  gem 'capistrano-bundler', '~> 1.6'
  gem 'capistrano-rbenv', '~> 2.1'
  gem 'capistrano-env-config'
  # gem 'capistrano3-puma', '=5.0.4', github: "seuros/capistrano-puma"
  gem 'capistrano-rpush'
  gem 'foreman'
  gem 'listen'
end

group :test do
  gem "capybara",                 "3.37.1"
  gem "selenium-webdriver",       "4.2.0"
  gem "webdrivers",               "5.0.0"
  gem "rails-controller-testing", "1.0.5"
  gem "minitest",                 "5.15.0"
  gem "minitest-reporters",       "1.5.0"
  gem 'guard',                    '2.18.0'
  gem "guard-minitest",           "2.4.6"
end

group :development, :production do
  gem 'rack-timeout'
end

group :production do
  gem "pg",         "1.3.5"
  gem "aws-sdk-s3", "1.114.0", require: false
end

gem 'aws-sdk', '~> 3'
#gem 'uppy-s3_multipart', '~> 0.3'
#gem 'uppy-s3_multipart', git: 'https://github.com/jshow/uppy-s3_multipart', branch: 'add_uploadid_partno_options_route'
gem 'uppy-s3_multipart', '>= 1.2.1'

gem 'sidekiq'
gem 'sidekiq-limit_fetch'
gem 'sidekiq-unique-jobs'
gem 'tunemygc', group: :production
gem 'oj'
gem 'rack-cors', :require => 'rack/cors'
gem 'sidekiq-scheduler', git: 'https://github.com/sidekiq-scheduler/sidekiq-scheduler', branch: 'v3-stable'
gem 'faraday'
gem 'paper_trail'
gem 'aasm'

gem 'gibbon'

gem 'state_machines-audit_trail', '>= 2.0.2'
gem 'state_machines-activerecord', '>= 0.8.0'
gem 'twilio-ruby'
gem 'down', '~> 5.0'
gem 'bcrypt', '3.1.18'
gem 'kaminari-activerecord'
gem 'webhookr', git: 'https://github.com/gerrypower/webhookr', branch: 'pass-hook-params-experimental'
gem 'webhookr-mailchimp'
gem 'webhookr-stripe', git: 'https://github.com/gerrypower/webhookr-stripe'
gem 'webhookr-mixpanel', git: "https://github.com/LifeTales/webhookr-mixpanel"
gem 'fastimage'
gem 'deep_cloneable'
gem 'webpush', '~> 1.0.0'
gem 'tracker', path: 'components/tracker'
gem 'commerce', path: 'components/commerce'
gem 'reminders', path: 'components/reminders'
gem 'sidekiq-cron', '~> 1.0.0'
gem 'whenever', require: false

gem 'fast_jsonapi', '~> 1.5', git: 'https://github.com/Netflix/fast_jsonapi'
gem 'gutentag', git: 'https://github.com/LifeTales/gutentag.git', branch: 'add_parent_polymoprhic'
gem 'rpush' #, '~> 4.1'


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem.
# Uncomment the following line if you're running Rails
# on a native Windows system:
# gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
