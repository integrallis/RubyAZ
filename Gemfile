source 'https://rubygems.org'
ruby "1.9.3"

gem 'rails', '3.0.7'
gem 'aws-s3', :require => 'aws/s3'
gem 'fog'
gem 'recaptcha', '~> 0.3.4', :require => 'recaptcha/rails'
gem 'rake', '0.9.2.2'
gem 'unicorn'
gem 'pg'
gem 'rails_12factor', group: :production

# REFINERY CMS ================================================================
# Anything you put in here will be overridden when the app gets updated.

gem 'refinerycms', github: 'integrallis/refinerycms'

group :development, :test do
  # To use refinerycms-testing, uncomment it (if it's commented out) and run 'bundle install'
  # Then, run 'rails generate refinerycms_testing' which will copy its support files.
  # gem 'refinerycms-testing',    '~> 0.9.9.16'
end

# END REFINERY CMS ============================================================

# USER DEFINED


# Specify additional Refinery CMS Engines here (all optional):
gem 'refinerycms-inquiries',    '~> 0.9'
gem 'refinerycms-news',         '~> 1.0'
gem 'refinerycms-portfolio',    '~> 0.9.9'
gem 'refinerycms-theming',      '~> 1.0'
gem 'refinerycms-search',       '~> 0.9.8'
gem 'refinerycms-blog',         '~> 1.3'
gem 'refinerycms-page-images',  '= 1.0.3'

# Add i18n support (optional, you can remove this if you really want to).
gem 'refinerycms-i18n',         '~> 0.9.9.16'

# END USER DEFINED
