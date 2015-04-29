# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts 'Run `bundle install` to install missing gems'
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  gem.name = 'ruby-style-guide'
  gem.homepage = 'http://github.com/theappbusiness/ruby-style-guide'
  gem.license = 'MIT'
  gem.summary = 'Gem to apply TAB code policies'
  gem.description = 'Run check_code to check code against policies'
  gem.email = 'will@theappbusiness.com'
  gem.authors = ["Will Thomas"]
  gem.add_dependency 'rubocop', '~> 0'
  gem.add_dependency 'bundler-audit', '~> 0'
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new
