
task default: [:update]

task :update_all do
  `git add .`
  `git commit -m "update"`
  `git push math461.wiki math461/wiki:master`
  `git push origin math461/wiki`
end

task :update do
  `git add .`
  `git commit -m "update"`
  `git push math461.wiki math461/wiki:master`
end