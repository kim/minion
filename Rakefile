require 'jeweler'

Jeweler::Tasks.new do |s|
  s.name = "minion_kim"
  s.description = "Super simple job queue over AMQP"
  s.summary = "Fork containing one simple patch. Will not be maintained if pull request #6 gets accepted upstream"
  s.authors = ["Orion Henry", "Kim Altintop"]
  s.email = "kim@soundcloud.com"
  s.homepage = "http://github.com/kim/minion"
  s.files = FileList["[A-Z]*", "{bin,lib,spec}/**/*"]
  s.add_dependency "amqp", ">= 0.6.7"
  s.add_dependency "bunny", ">= 0.6.0"
  s.add_dependency "json", ">= 1.2.0"
end

desc 'Run specs'
task :spec do
  sh 'bacon -s spec/*_spec.rb'
end

task :default => :spec
