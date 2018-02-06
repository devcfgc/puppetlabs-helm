source ENV['GEM_SOURCE'] || 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_GEM_VERSION') ? ENV['PUPPET_GEM_VERSION'] : ['>= 3.3']
gem 'metadata-json-lint'
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 1.2.0'
gem 'puppet-lint', '>= 1.0.0'
gem 'facter', '>= 1.7.0'
gem 'rspec-puppet'
gem "rspec-retry"
gem 'thor'
gem 'semantic_puppet'
gem 'simplecov'
gem 'simplecov-json'
gem 'simplecov-rcov'
gem "beaker-puppet_install_helper", :require => false
gem "beaker-rspec"
gem "parallel_tests"
gem "beaker", "~> 2.0"
gem 'rspec_junit_formatter'
gem "puppet-lint-i18n"
gem "puppet_pot_generator"
gem 'rubocop-i18n'
gem 'gettext-setup'
gem 'rubocop-rspec'

# rspec must be v2 for ruby 1.8.7
if RUBY_VERSION >= '1.8.7' && RUBY_VERSION < '1.9'
  gem 'rspec', '~> 2.0'
  gem 'rake', '~> 10.0'
else
  # rubocop requires ruby >= 1.9
  gem 'rubocop', '~> 0.49.0'
end
