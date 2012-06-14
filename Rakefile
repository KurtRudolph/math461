
task default: [:update]

task :update do
  `git add .`
  `git commit -m "update"`
  `git push math461.wiki math461/wiki:master`
  `git push math461 math461/wiki:wiki`
end