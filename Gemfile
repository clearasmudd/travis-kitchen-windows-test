# -*- mode: ruby -*-
# vi: set ft=ruby :

source 'https://rubygems.org'
gemspec

gem 'rake'
# gem 'berkshelf', '~> 4.0'

group :integration do
  gem 'test-kitchen', '~> 1.2'
  gem "kitchen-inspec"
  gem 'kitchen-salt', '>= 0.6.0'
  gem 'safe_yaml'
  gem 'train'
end

group :vagrant do
  gem 'vagrant-wrapper', '~> 2.0'
  gem 'kitchen-vagrant', '~> 0.18'
end

group :docker do
  gem 'kitchen-docker', '~> 2.1.0'
end