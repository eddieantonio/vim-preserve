# Preserve

A [Pathogen][]/[Vundle][]-managable package for the Preserve function. Because
we like our vimrcs to be tidy!

Full credit for Preserve goes to the [The Doctor What][docwhat] who based it
on [Jonathan Palardy's][provenance] original post. Props to [Drew Neil][] too!

## Sample maps

    " Re-indents buffer.
    nmap <silent> <Leader>= :call Preserve("normal gg=G")<CR>
    " Removes all trailing whitespace in buffer.
    nmap <silent> <Leader>$ :call Preserve("%s/\\s\\+$//e")<CR>

[Pathogen]: https://github.com/tpope/vim-pathogen
[Vundle]: https://github.com/gmarik/vundle
[docwhat]: https://docwhat.org/vim-preserve-your-cursor-and-window-state/
[provenance]: http://technotales.wordpress.com/2010/03/31/preserve-a-vim-function-that-keeps-your-state/
[Drew Neil]: http://vimcasts.org/episodes/tidying-whitespace/
