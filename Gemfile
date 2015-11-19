source 'https://rubygems.org'

group :lint do
  gem 'foodcritic', '~> 5.0'
  gem 'rubocop', '~> 0.35'
end

group :unit do
  gem 'berkshelf',  '~> 3.1.5' # pin to 3.1 due to performance issues on mac
  gem 'chefspec',   '~> 4.4'
end

group :integration do
  gem 'test-kitchen', '~> 1.4'
  gem 'kitchen-vagrant', '~> 0.18'
  gem 'winrm-transport', '~> 1.0'
end
