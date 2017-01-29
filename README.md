# :bullettrain_side: gitgit 
------
My approach to Github projects management.
Recently I made a Winter Clean on my machine ( basically, I wipe the disk and install a new Linux distribution).
I'm not the sentimental type towards my files so I pretty much kept only the essential.
But then I realize... All my Github projects and all the ones that I like to follow and keep were gone :(
So, with this in mind, this script objective is to simplify the process of cloning all your favorite projects again.
It's a work in progress but you can already save some work with it.

###How does it work?

Basically, I create a dir in my home folder ~/git_repos where I'll clone all the project repos
Inside this dir, there is also a hidden file .gitgit that keeps track of the project repos you are interested in

###How to use?

1. Make the script executable 

2. Use it like:
```
$ gitgit -a ludeed\gitgit
```
This will add this repository to your personal gitgit file
Do this for every project you want, with this syntax:
(basically the end of the URL)
```
$Username\$RepoName
```
After that, just type:
```
$ gitgit -c
```
The script will clone all the repos you indicated.

###TODO

Many Things!
