# SpellJS Product

## Prerequisites

### Linux prerequisites

* Install git, make 


* Install NodeJS

### Windows prerequisites

* Install Git Bash (use this for all git related commands. The git version in cygwin is too outdated to do the checkout properly) 

* Install Cygwin (32 bit) with the following packages: 
bc, bison, bzip2, ca-certificates, curl, diffutils, e2fsprogs, emacs, flex, gcc-core, gcc-g++, git, cygwin64-gcc, 
cygwin64-gcc-g++, gperf, keychain, make, nano, openssh, patch, perl, perl-libwin32, python, rebase, rsync, ruby,
subversion, unzip, vim, zip

* Make sure that `autocrlf = false` in your `~/.gitconfig`

* Install NodeJS

### MacOSX prerequisites

* Install NodeJS


## How to get started

```shell

git clone https://github.com/Spielmeister/spellJS.git

cd spellJS

./git_update_submodules

#run this script a second time to checkout all submodules
./git_update_submodules 

cd spellCore && make && cd ..

cp spellCli/spellConfig.json.template spellCli/spellConfig.json

cd spellEd && ./start_dev_spelledserver $PATH_TO_YOUR_SPELL_WORKSPACE

```