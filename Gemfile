source "https://rubygems.org"

gemspec

if as = ENV['AS_VERSION']
  gem 'activesupport', "~> #{as}"
end

group :deployment do
  gem 'package_cloud'
  gem 'rake'
end
