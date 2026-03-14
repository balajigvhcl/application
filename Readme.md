##### working with git 

# create a dir named 'working'
balaj@Balaji MINGW64 ~/working (main)


# create 2 text files inside the directory
balaj@Balaji MINGW64 ~/working (main)
$ dir
FileA.txt  FileB.txt
$
# initialising an empty git reposity on the  'working' directory
balaj@Balaji MINGW64 ~/working (main)
$ git init
Initialized empty Git repository in C:/Users/balaj/working/.git/
$
# We are providing the global user name and email - for the user working on it.
balaj@Balaji MINGW64 ~/working (master)
$ git config --global user.name 'Balaji GV'

balaj@Balaji MINGW64 ~/working (master)
$ git config --global user.email 'balajigv.me@gmail.com'

balaj@Balaji MINGW64 ~/working (master)

---------------------------------------------------------------
# adding files to git #### 
# working dir --- staging ---- .git directory (git repository)

balaj@Balaji MINGW64 ~/working (master)
$ git add .

balaj@Balaji MINGW64 ~/working (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   FileA.txt
        new file:   FileB.txt
        new file:   Readme.md
# note the file (status changed from U to A)

balaj@Balaji MINGW64 ~/working (master)
$ git commit -m 'this is the initial commit'
[master (root-commit) 3fed556] this is the initial commit
 3 files changed, 31 insertions(+)
 create mode 100644 FileA.txt
 create mode 100644 FileB.txt
 create mode 100644 Readme.md


