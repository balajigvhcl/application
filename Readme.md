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

