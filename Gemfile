source 'https://rubygems.org'
gemspec

logstash_path = ENV["LOGSTASH_PATH"] || "./logstash"

gem 'logstash-core', :path => "#{logstash_path}/logstash-core"
gem 'logstash-core-plugin-api', :path => "#{logstash_path}/logstash-core-plugin-api"

gem 'prometheus-client', '~> 2.1'
gem 'rack', '~> 2.2', '>= 2.2.3'

gem 'logstash-devutils', '~> 2.0', '>= 2.0.4'
