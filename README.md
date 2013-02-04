![](https://raw.github.com/adrianolaru/adio-theme/master/images/adio-theme.png)

#Adio

Adio is dark theme for iTerm2, tmux and Vim. The Vim colorscheme is made for
terminals suporting 256 colors only.

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

For example, if you have Vundle installed, you just declare a bundle in your
`.vimrc', and then run :BundleInstall vim command.

    Bundle 'adrianolaru/vim-adio'

