require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    s.name = "slim-attributes"
    s.summary = "Slim-attributes - lazy instantiation of attributes for ActiveRecord"
    s.email = "sdsykes@gmail.com"
    s.homepage = "http://github.com/sdsykes/slim-attributes"
    s.description = "Slim attributes boosts speed in Rails/Mysql ActiveRecord Models by avoiding
    instantiating Hashes for each result row, and lazily instantiating attributes as needed."
    s.authors = ["Stephen Sykes"]
    s.files = FileList["[A-Z]*", "{ext,lib,test}/**/*"]
    s.extensions = "ext/extconf.rb"
    s.rubyforge_project = 'slim-attributes'
  end
  Jeweler::GemcutterTasks.new
  Jeweler::RubyforgeTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://
gems.github.com"
end

task :rdoc do
  `mkdir rdoc`
  `echo documentation is at http://github.com/sdsykes/slim-attributes > rdoc/README.rdoc`
end
