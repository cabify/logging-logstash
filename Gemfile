source 'https://rubygems.org'


group :development, :test do
  gem "rspec"
  gem "timecop", "~> 0.7.1"
  # Including gems below as dependencies with gemspec generates undefined method 'init' error
  gem "logging", "1.8.2"
  gem "logstash-logger", "~> 0.7.0"
end

group :test do
  gem "rspec_junit_formatter"
  gem 'simplecov'
  gem 'simplecov-csv'
end

# Specify your gem's dependencies in logging-logstash.gemspec
# gemspec