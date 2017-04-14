dotfiles working under cygwin

don't forget to
`git pull --recurse-submodules`
`git pull --recurse-submodules  && git submodule update --recursive`
`source ~/.bashrc`
`git submodule update --recursive`
`git submodule init`
`git submodule update`
`$ cd dotfiles`
`git submodule update --init --recursive`

generate dotfiles and symlinks
`chmod u+x makesymlinks.sh`

eventually pull latest masters
`git submodule update --remote`

