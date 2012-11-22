class Server < Thor
  include Thor::Actions

  default_task :start

  desc "start", "Start the server"
  def start
    run "bundle exec jekyll --server --auto --base-url=''"
  end

end
