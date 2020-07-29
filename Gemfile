source 'https://rubygems.org'

gemspec

logstash_path = "./"

#if Dir.exist?(logstash_path) && ENV["LOGSTASH_SOURCE"] == "1"
  gem 'logstash-core', :path => "#{logstash_path}/logstash-core"
  gem 'logstash-core-plugin-api', :path => "#{logstash_path}/logstash-core-plugin-api"
  gem 'logstash-devutils', :path => "#{logstash_path}/logstash-devutils"
#end

if RUBY_VERSION == "1.9.3"
  gem 'rake', '12.2.1'
end
