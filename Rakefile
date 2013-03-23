task default: [:deploy]

task :deploy do
  sh "rsync -rtz --delete public/ wf:~/webapps/wmleeds/"
end
