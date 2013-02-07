![](https://raw.github.com/adrianolaru/adio-theme/master/images/adio-theme.png)

#Adio

Adio is dark theme for iTerm2, tmux and Vim. The Vim colorscheme is made for
terminals suporting 256 colors only and the syntax highlighting is based on
Molokai colorscheme.

## iTerm2

Download `adio.itermcolors` file somewhere, open iTerm2 app, then go to
Preferences-Profiles-Colors-Load Presets-Import... to import it.

## tmux 

Download `adio.tmuxcolors` file somewhere and source it in your `.tmux.conf`
configuration file:

    # in your .tmux.conf
    # load tmux colors
    source ~/.adio.tmuxcolors  

## Vim 

I've made a [separate repository](https://github.com/adrianolaru/vim-adio) for
Vim colorscheme to easily be installed by using a plugin manager like
[Vundle](https://github.com/gmarik/vundle) or
[Pathogen](https://github.com/tpope/vim-pathogen).

For example, if you have Vundle installed, you just declare the bundle you wish
to install in your `.vimrc`, and then run `:BundleInstall` Vim command.

    Bundle 'adrianolaru/vim-adio'

## Prompt

In case you wonder, my prompt is declared in my [bash_profile](https://github.com/adrianolaru/dotfiles/blob/master/bash_profile) as:

    export PS1='┌─[\[\e[38;5;32m\]\w\[\e[0m\]\[\e[38;5;240m\]$(__git_ps1 " (%s)")\[\e[0m\]]\n└─╼ '

where `__git_ps1` is a function from [git-prompt.sh](https://github.com/git/git/blob/master/contrib/completion/git-prompt.sh), a bash script that comes with Git.
