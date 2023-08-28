# set proxy & unset proxy 
- set proxy commond : export http_proxy=127.0.0.1:8889
- unset proxy commond : unset http_proxy
- chek proxy commond : wget www.google.com
  
# repo-init
- git clone https://gerrit.googlesource.com/git-repo
- cd git-repo
- git reset --hard v1.13.11
- mkdir -p ~/.bin
- PATH="${HOME}/.bin:${PATH}"
- cp repo ~/.bin/repo
- chmod a+rx ~/.bin/repo

# Setting python xxx as default on Linux
- sudo update-alternatives --config python
