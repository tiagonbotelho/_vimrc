My Personal VimRC
=================

##Plugins Used
  To install Plugin's in my .vimrc i'm using [Vundle](https://github.com/gmarik/Vundle.vim) since it is the best Plugin Manager.
  
  [UltiSnips](https://github.com/SirVer/ultisnips):
Together with [vim-snippets](https://github.com/honza/vim-snippets) it makes a very powerful Addon to have in vim
    
  [NerdTree](https://github.com/scrooloose/nerdtree):
**NerdTree** is a useful Plugin to use when you are looking for a file in a specific directory and when you want to see the file structure of your project.

  [NerdCommenter](https://github.com/scrooloose/nerdcommenter):
**NerdCommenter** is very useful when it comes to comment several or even one line of code! to see the specific mappings of the Plugin see the docs of the link provided above.

  [Syntastic](https://github.com/scrooloose/syntastic):
**Syntastic** is a very useful linter that checks your syntax and common errors (such as missing ; and not initialized variables) it is very good for distracted people!


  [LaTeX](https://github.com/LaTeX-Box-Team/LaTeX-Box):
I'm a big fan of editing text with LaTeX since it makes files look very professional so i had to look for a plugin to use when editing LaTeX in vim, this is the one i came up with!


  [Git-Gutter](https://github.com/airblade/vim-gitgutter):
I installed this one just for convenience, i use Git alot so it's very good for me to be able to see the changes i'm making when i'm coding, it will add a **+** when something was added and **-** when deleting something from the file


  [Tabular](https://github.com/godlygeek/tabular):
Personally this is one of my favorite Plugin's for vim, it makes things super pretty making text more tabular you can see examples in the link provided above.

  [Super-Tab](https://github.com/ervandew/supertab):
I only use it because i hate to type the same variables over and over again so it's very useful if you are a lazy person

  [CTRL-P](https://github.com/kien/ctrlp.vim):
I personally use a MacBook Pro with Alfred Plugin(for those that don't know what Alfred is, it's an alternative for Spotlight), this can be compared to that but for vim, it searches every file by name, it is really usefull when you don't know where to find the file

  [Surround](https://github.com/tpope/vim-surround):
Really good time saver when it comes to change some item by another eg: "->' I'm still exploring it so I don't know much about it yet but the documentation is really clear

  [Auto Pair](https://github.com/jiangmiao/auto-pairs):
This one speaks for itself basically closes brackets, " , curly-braces, etc automatically

  [Gist](https://github.com/mattn/gist-vim):
A very simple and useful way to make Gists! just Simply type :Gist and it will generate a Gist for you see docs on how to configure it


##Mappings

I turn left and right arrows off since i don't have any use to them.

Up and Down arrow on the other hand:

    no <up> ddkP
    no <down> ddp
These mappings make it possible to move the current line text through the file

(I will be adding new mappings as e explore vim more and more)

## Screenshot

![Screenshot](http://i.imgur.com/RJ7xfDm.png)


##Installation

    git clone git@github.com:tiagonbotelho/vimrc.git
    cd vimrc/
    mv .vimrc ~ && mv -R .vim ~
