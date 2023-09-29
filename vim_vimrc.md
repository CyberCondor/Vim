```vimrc
" Set shift width to 4 spaces.
set shiftwidth=4

" Set tab width to 4 columns.
set tabstop=4

" Use space characters instead of tabs.
set expandtab

" set relativenumber then set number to show relative number as current line number
set relativenumber
set number 

" Auto Indent
set autoindent

" syntax highlighting
syntax on

" Enable type file detection.
filetype on

" Set the history length.
set history=1000

" Set no word wrap.
set nowrap

" Enable auto completion menu after pressing TAB.
set wildmenu

" Make wildmenu behave like similar to Bash completion.
set wildmode=list:longest

" There are certain files that we would never want to edit with Vim... ->
"     Wildmenu will ignore files with these extensions.
set wildignore=*.docx,*.jpg,*.png,*.gif,*.pdf,*.pyc,*.exe,*.flv,*.img,*.xlsx

" Enable Mouse Handline
set mouse=a
```

---
#
#