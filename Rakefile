require 'rake'

desc 'Serve it'
task :serve do
    sh "bundle exec jekyll serve"
end

desc 'Preview the site with Jekyll'
task :preview do
    sh "bundle exec jekyll serve --watch --drafts --baseurl '' "
end

desc 'Search site and print specific deprecation warnings'
task :check do 
    sh "bundle exec jekyll doctor"
end
