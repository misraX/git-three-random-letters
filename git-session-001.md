# Git - The random three-letter 001

### Git - Config:

Your regural copy and paste commands :D 

`git config --global user.name "misrax"`

`git config --global user.email "maysragamal@gmail.com"`

But wait, what ? how ? why not --local :D ? or --system...

--global ~/.gitconfig

--local .git/config

--system /etc/gitconfig

### Git in three steps:

```bash
$ cd ~/Documents/django-app # mmm :D Change directory to webapp.
$ git init      (1) # Initialize a repo.
$ touch README.md # Create a file.
$ git add README.md     (2) # Add the file to the repo.
$ git commit -m "My first commit."  (3) # Your first commit.
```

### Git - states:

1. Unstaged / Staged

2. Untracked / Tracked

3. Unmodified / Modified

4. Commited


### Deep dive:

`$ touch start.py # Creating a new file`

let's check the status

`$ git status # Untracked file start.py`

let's track/stage `start.py`

`git add start.py` git will stage the changes for the next commit.

Now let's play...

Add changes to start.py

`echo "print('Hello World!')" >> start.py`

let's check the status 

`git status` surpirse....

Mission complete...

`git commit -m "Hello World.."`


### Branch

Git branch is a pointer.

>Facts: By default git names the first pointer/branch "master", but when ?

`cd ~/Documents/javascript-app`

`git init`

`touch index.js` 

`git log`

`git branch`

`git add index.js`

`git commit -m "Just another index.js"`

`git branch`

`git log`

### Next:

The merge.
Advanced git structure.