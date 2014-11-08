# Mod base16 railscasts
this is a slightly modified version of the railscasts colorscheme from the [Base16 repository](https://github.com/chriskempson/base16-vim/blob/master/colors/base16-railscasts.vim) to meet my requirements.
This colorscheme was only tested with iTerm using the color profile found [mod_base16_railscasts.itermcolors](mod_base16_railscasts.itermcolors)
which is also a modified version of the original profile found under [Base16-iterm2](https://github.com/chriskempson/base16-iterm2)

I didn't created a fork, as i only modified the colorscheme railscasts and will only use this colorscheme.

For more information check the original [Base16 repository](https://github.com/chriskempson/base16)

## Installation
1. first import the iterm colort  profile
    * On iTerm2, go to Preferences > Profiles > Colors
    * Click on Load Presets > Import and import your favorite theme from this repo
    * Load the theme by clicking on Load Presets and selecting it

2. set the colorscheme on vim
    add the following lines to your `~/.vimrc` 
    ```
    set background=dark
    colorscheme mod-base16-railscasts
    ```

### Vundle
Add the following to your `~/.vimrc` file and run `PluginInstall` in Vim.

    Plugin 'juanolon/mod-base16-railscasts'

### Pathogen

    cd ~/.vim/bundle
    git clone https://github.com/juanolon/mod-base16-railscasts.git

### Manual

    cd ~/.vim/colors
    git clone git@github.com:juanolon/mod-base16-railscasts.git mod-base16-railscasts
    cp mod-base16-railscasts/colors/*.vim .
