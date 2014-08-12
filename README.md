get newest version from https://github.com/zendtech/ZendOptimizerPlus/releases 
git-import-orig ../{package}.tar.gz


build command:
  git-buildpackage --git-pbuilder --git-dist=wheezy --git-arch=amd64 --git-debian-branch=master
