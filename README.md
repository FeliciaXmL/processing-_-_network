Skip to content
FeliciaXmL
/
processing-_-_network
Template
Code
Issues
Pull requests
2
Discussions
Actions
Projects
1
Wiki
Security
Insights
Settings
Update ClarityInFocus. ANN
CI #3
build
succeeded 1 minute ago in 3s
2s
Current runner version: '2.275.1'
Operating System
  Ubuntu
  18.04.5
  LTS
Virtual Environment
  Environment: ubuntu-18.04
  Version: 20210111.1
  Included Software: https://github.com/actions/virtual-environments/blob/ubuntu18/20210111.1/images/linux/Ubuntu1804-README.md
Prepare workflow directory
Prepare all required actions
Getting action download info
Download action repository 'actions/checkout@v2'
1s
Run actions/checkout@v2
  with:
    repository: FeliciaXmL/processing-_-_network
    token: ***
    ssh-strict: true
    persist-credentials: true
    clean: true
    fetch-depth: 1
    lfs: false
    submodules: false
Syncing repository: FeliciaXmL/processing-_-_network
Getting Git version info
  Working directory is '/home/runner/work/processing-_-_network/processing-_-_network'
  /usr/bin/git version
  git version 2.30.0
Deleting the contents of '/home/runner/work/processing-_-_network/processing-_-_network'
Initializing the repository
  /usr/bin/git init /home/runner/work/processing-_-_network/processing-_-_network
  hint: Using 'master' as the name for the initial branch. This default branch name
  hint: is subject to change. To configure the initial branch name to use in all
  hint: of your new repositories, which will suppress this warning, call:
  hint: 
  hint: 	git config --global init.defaultBranch <name>
  hint: 
  hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
  hint: 'development'. The just-created branch can be renamed via this command:
  hint: 
  hint: 	git branch -m <name>
  Initialized empty Git repository in /home/runner/work/processing-_-_network/processing-_-_network/.git/
  /usr/bin/git remote add origin https://github.com/FeliciaXmL/processing-_-_network
Disabling automatic garbage collection
  /usr/bin/git config --local gc.auto 0
Setting up auth
  /usr/bin/git config --local --name-only --get-regexp core\.sshCommand
  /usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
  /usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
  /usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
  /usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
Fetching the repository
  /usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +7626f8725702bf4c57e99e1e4e72405e6a5c3cd6:refs/remotes/pull/2/merge
  remote: Enumerating objects: 12, done.        
  remote: Counting objects:   8% (1/12)        
  remote: Counting objects:  16% (2/12)        
  remote: Counting objects:  25% (3/12)        
  remote: Counting objects:  33% (4/12)        
  remote: Counting objects:  41% (5/12)        
  remote: Counting objects:  50% (6/12)        
  remote: Counting objects:  58% (7/12)        
  remote: Counting objects:  66% (8/12)        
  remote: Counting objects:  75% (9/12)        
0s
0s
0s
0s
