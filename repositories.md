Repositories
============

### Start a repository from scratch

#### Online Repository
Online:
* Go to github account
* Click "Create repository"


#### Local Repository
In Terminal:
* mkdir ~/_repoName_
* cd ~/_repoName_
* git init
* git remote add origin https://github.com/_yourUserName_/_repoName_.git


### Fork another user's repository

#### Online Repository
Online:
* click "Fork" button in repository

#### Clone Repository
In Terminal:
* git clone https://github.com/_yourUserName_/_repoName_.git


Basic Git commands
==================
### Adding
* git add . 'adds all new files'
* git add -u 'updates tracking for files that changed names or were deleted
* git add -A 'does both of the previous'

### Committing
* git commit -m "message"
