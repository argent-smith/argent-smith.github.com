# 
# To change this template, choose Tools | Templates
# and open the template in the editor.
 

require 'rubygems'
require 'rake'
require 'rake/clean'
require 'rake/gempackagetask'
require 'rake/testtask'

desc 'just generate the site'
task :generate do
  sh "jekyll"
end

desc 'serve locally'
task :serve do
  sh "jekyll --server --auto"
end