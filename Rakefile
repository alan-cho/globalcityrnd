require 'rake'

desc "Start the Jekyll development server"
task :start do
  sh "bundle exec jekyll serve"
end

desc "Start the Jekyll server with live reload"
task :dev do
  sh "bundle exec jekyll serve --livereload"
end

desc "Start the Jekyll server on port 3000"
task :start3000 do
  sh "bundle exec jekyll serve --port 3000"
end

desc "Build the site for production"
task :build do
  sh "bundle exec jekyll build"
end

desc "Clean the build directory"
task :clean do
  sh "bundle exec jekyll clean"
end

desc "Install dependencies"
task :install do
  sh "bundle install"
end

# Make 'start' the default task
task default: :start

