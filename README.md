  488  git clone https://github.com/tdangles81/phase-0-gps-1.git
  Makes a copy of the repo on local disk.
  489  ls
  List files within working directory.
  490  cd phase-0-gps-1
  Making cloned repo my working directory.
  491  cd ..
  Change directory to parent directory.
  492  cd phase-0-gps-1/
  493  touch awesome_page.md
  Used touch to create a file within working directory.
  494  ls
  List contents of the working directory.
  495  git add awesome_page.md
  Stages files for commit.
  496  ls
  497  git status
  Shows changes/states of commit.
  498  git commit -m "Added awesome_page"
  Commits files with a commit message.
  499  git status
  502  git push origin master
  Push commit to master on Github.
  503  ls
  504  git checkout -b "add-command-log"
  Add a new branch from the master and named it.
  505  -b help
  506  git branch
  Checked current branch.
  507  ls
  508  open README.md
  509  subl README.md
  Open README.md in sublime text editor.
  510  history 20
  Check previous 20 commands.
  511  history 20 >> README.md
  512  history 30  >> README.md
