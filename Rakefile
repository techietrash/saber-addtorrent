task :build do
  run "coffee -c --bare -p lib/main.coffee > output/main.user.js"
end

task :watch do
  run "watchr addtorrent.watchr &>/dev/null &"
end

def run(cmd)
  puts cmd
  system cmd
end

