require 'html-proofer'

task :default do
  sh "bundle exec jekyll build"
  options = { :assume_extension => true, :disable_external => true, :http_status_ignore => true, :url_ignore => ['/auth/logout'] }
  HTMLProofer.check_directory("./_site", options).run
end

task "assets:precompile" do
  exec("jekyll build")
end
