source 'https://rubygems.org'

gem "puppet",             "~> 4.10.12"
gem "facter",             "< 3"
gem 'safe_yaml',          "~> 1.0.4"

# json_pure and json have been pinned to before version 2.0
# as versions have no support for ruby 1.9.3 and greater
#gem 'json_pure', '< 2'
#gem 'json',      '< 2'


group :test do
  gem 'puppet-lint'
  gem 'rspec-puppet', '~> 2.7.0'
  gem 'metadata-json-lint'
end

group :development, :test do
  gem 'rake'
  gem 'puppetlabs_spec_helper'
end
