LithoChromatic Color Theme.
===============================================================================

A clear, consistent and vibrant color theme for Vim.

Synopsis
-------------------------------------------------------------------------------

Lithochromatic is a theme that aims better readabilty. It uses a small color  
set.

One of main concerns is to be consistent in highlighting, which means  
using same or related colors for related elements of source code. This makes  
maintaining concentration while editing and reading easier.

Recently I have changed whole color set of LithoChromatic from a less  
consistent set to a better one. I have also set colors for gvim this time.

Installing
-------------------------------------------------------------------------------
If you have [Pathogen][1], or alike, just clone this repo to your  
`~/.vim/bundle/`:

    $ cd ~/.vim/bundle/
    $ git clone https://github.com/gkya/lithochromatic-vim.git

Otherwise, get the `colors/lithochromatic.vim` file from this repository's  
tree, and put it into `~/.vim/colors/`:

    $ mkdir ~/.vim/colors/ # if you dont have it there already
    $ curl https://raw.github.com/gkya/\
    lithochromatic-vim/master/colors/lithochromatic.vim >> \
    ~/.vim/colors/lithochromatic.vim

Then set your colorscheme to _lithochromatic_:

    if &term=~'xterm' || has("gui_running")
        set t_Co=256
        colorscheme lithochromatic
    endif

__Important__: This color scheme has no support for non-256-color terminals.  

[1]: https://github.com/tpope/vim-pathogen "Pathogen"
