source 'https://rubygems.org'

# Declare your gem's dependencies in forest.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use a debugger
gem 'byebug', group: [:development, :test]

group :test do
  gem 'rake'
  gem 'sqlite3'
end

#gem 'active_model_serializers', path: '~/workspace/internal/active_model_serializers'
gem 'jsonapi-serializers'
gem 'rack-cors', :require => 'rack/cors'
