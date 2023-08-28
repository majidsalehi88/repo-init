# rerepo init

git clone https://gerrit.googlesource.com/git-repo
cd git-repo
git reset --hard v1.13.11
mkdir -p ~/.bin
PATH="${HOME}/.bin:${PATH}"
cp repo ~/.bin/repo
chmod a+rx ~/.bin/repo
