require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    $NAME = gem.name = 'pageranker'
    $VERSION = File.exist?('VERSION') ? File.read('VERSION').strip : ''
    $SUMMARY = gem.summary = 'Check the PageRank of a website'
    $DESCRIPTION = gem.description = 'Check the PageRank of a website.'
    $EMAIL = gem.email = 'enrico@megiston.it'
    $HOMEPAGE = gem.homepage = 'http://github.com/pioz/pageranker'
    $AUTHORS = gem.authors = [ 'Enrico Pilotto' ]
  end
rescue LoadError
  puts 'Jeweler (or a dependency) not available. Install it with: gem install jeweler'
end

require 'rake/rdoctask'
Rake::RDocTask.new do |rdoc|
  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = "pageranker #{$VERSION}"
  rdoc.rdoc_files.include('README*')
end
