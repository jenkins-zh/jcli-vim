# vim for jcli

You need setup [VundleVim](https://github.com/VundleVim/Vundle.vim) first.

# .vimrc

Suggestion configuration:


```
set nocompatible              " be iMproved, required
filetype off                  " required

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()
" alternatively, pass a path where Vundle should install plugins
"call vundle#begin('~/some/path/here')

" let Vundle manage Vundle, required
Plugin 'VundleVim/Vundle.vim'
Plugin 'jenkins-zh/jcli.vim'
Plugin 'kien/ctrlp.vim'
Plugin 'vim-airline/vim-airline'
Plugin 'christianrondeau/vim-base64'

" All of your Plugins must be added before the following line
call vundle#end()            " required
filetype plugin indent on    " required

```

# Syntax
Follow the instructions by [Jenkinsfile-vim-syntax](https://github.com/martinda/Jenkinsfile-vim-syntax) to enable Jenkinsfile syntax.

# References
https://learnvimscriptthehardway.stevelosh.com/
