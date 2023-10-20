set scrolloff=10
set incsearch
set hlsearch
set number relativenumber
"set keep-english-in-normal-and-restore-in-insert
set commentary
set wrap
inoremap jj <Esc>
inoremap <C-h> <Left>
inoremap <C-j> <Down>
inoremap <C-k> <Up>
inoremap <C-l> <Right>
inoremap <C-d> <backspace>
inoremap <C-e> <End>
inoremap <C-w> <Home>
" 将一行向上移动
inoremap mk <Esc>kddpk
nnoremap mk kddpk
" 将一行向下移动
inoremap mj <Esc>ddp
nnoremap mj ddp
"共享剪切板
set clipboard+=unnamed
