# vimConf

## add the following in .vimrc
execute pathogen#infect()

filetype plugin indent on
syntax enable
set background=dark
let g:solarized_termcolors=256
let g:solarized_termtrans=1
let g:solarized_degrade=1
let g:solarized_bold=1
let g:solarized_underline=1
let g:solarized_italic=1
let g:solarized_contrast ="high"
let g:solarized_visibility="high"
colorscheme solarized

set nu
set tabstop=2
set shiftwidth=2
set hlsearch

"nerd tree config
autocmd StdinReadPre * let s:std_in=1
autocmd vimenter * if argc() == 0 && !exists("s:std_in") | NERDTree | endif
