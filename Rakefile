# -*- ruby -*-
$:.unshift(File.dirname(__FILE__)+"/lib")
require 'rubygems'
require 'hoe'
require 'rserve'
Hoe.plugin :git
Hoe.spec 'rserve-client' do
   self.testlib=:rspec
   self.test_globs="spec/*_spec.rb"
   self.version=Rserve::VERSION
   self.rubyforge_name = 'ruby-statsample' # if different than 'rserve'
   self.remote_rdoc_dir = "rserve-client"
   self.developer('Claudio Bustos', 'clbustos_AT_gmail.com')
end

# vim: syntax=ruby
