# [gmarik](http://github.com/gmarik)'s [Vim configuration](http://github.com/gmarik/vimfiles)

to try it out:

    $ mkdir -p /tmp/vimtest && cd !$                                         # create and cd to test folder
    $ git clone --recursive https://github.com/gmarik/vimfiles.git ./.vim    # clone recursively with vundle
    $ HOME=$(pwd) vim -u .vim/vimrc +BundleInstall                           # run installation in relative to current folder
                                                                           # and using downloaded `vimrc`
