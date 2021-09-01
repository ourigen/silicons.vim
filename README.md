# silicons.vim

`silicons.vim` is a simpler alternative to [vim-devicons](https://github.com/ryanoasis/vim-devicons), providing filetype
icons that dynamically changes depending on the language of the file. Its main function is to be integrated into the
Vim/Neovim statusline. It is integrated by default in [skyline.vim](https://github.com/ourigen/skyline.vim), but it is
simple to add this to your custom statusline using

```vim
set statusline+=%{silicons#get_icons(bufname(''))}
```

Yep, that's it.
