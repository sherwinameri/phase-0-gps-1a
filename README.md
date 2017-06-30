# phase-0-gps-1a

361  mkdir phase-0-gps-1a # creating a directory
  362  ls # listing files in dir
  363  cd phase-0-gps-1a # changing dir
  364  git clone https://github.com/sherwinameri/phase-0-gps-1a.git # retrieving repository from GitHub via URL
  368  touch awesome_page.md # add file to folder
  369  git add awesome_page.md # adds modified file to stage (files to be committed)
  370  git commit -m "Initial commit" # commits files on the stage (creates "save points" with commments)
  371  git status # checks to see what's on the stage, added but not committed, as well as modified before adding (working dir)
  372  git push origin master # pushes commit/changes to GitHub (remote local)
  373  git remote -v # viewing upstream destinations
  374  git checkout -b add-command-log # adds branch
  376  git branch # shows which branches exist and which one you're in
  381  git checkout master # switches to master
  383  subl . # opens folder in sublime
  386  rm on-this-branch.md # remove a file from dir
  389  history # view command line history
