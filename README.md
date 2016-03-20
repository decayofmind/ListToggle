ListToggle
==========

It's a fork of [Valloric/ListToggle][], allowing you mapping keys another way.

A simple vim plugin for toggling the display of the quickfix list and the
location-list. Install it with [vim-plug][] or any other plugin manager.

    Plug 'decayofmind/ListToggle'

You can set the key mappings for toggling Vim's `locationlist` and `quickfix`
windows in your vimrc file:

    nmap <Leader>q <Plug>QToggle
    nmap <Leader>l <Plug>Ltoggle

By default, they are set to `<leader>l` and `<leader>q`, respectively.

Here's how you can set the height (in number of lines) of the spawned window:

    let g:lt_height = 10

[Valloric/ListToggle]: https://github.com/Valloric/ListToggle
[vim-plug]: https://github.com/junegunn/vim-plug

