source 'https://rubygems.org'

gem 'metadata-json-lint'
gem 'puppetlabs_spec_helper', '>= 0.1.0'
gem 'puppet-lint',            '>= 1.0.0'
gem 'ruby-augeas',            :require => false
gem 'rspec-puppet-augeas',    :require => false


if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion,  :require => false
else
  gem 'puppet',                 :require => false
end

# rspec must be v2 for ruby 1.8.7
if RUBY_VERSION >= '1.8.7' and RUBY_VERSION < '1.9'
  gem 'rspec', '~> 2.0'
end

# vim:ft=ruby
