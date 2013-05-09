# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "reveal_rails"
  gem.homepage = "http://github.com/miamiruby/reveal_rails"
  gem.license = "MIT"
  gem.summary = %Q{Reveal Modals in rails}
  gem.description = %Q{Reveal Modals Gem Package}
  gem.email = "paul_moises+miamiruby+mzararagoza@moiseszaragoza.com"
  gem.authors = ["Paul Kruger and Moises Zaragoza"]
end
Jeweler::RubygemsDotOrgTasks.new

task :default => :test

