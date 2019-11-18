# Dotfiles

Those are my personal dotfiles. Or at least the ones that I care about.

### i3

It has i3-bar with a custom color scheme matching my current pywal scheme. It was modified manually, so when using a different color scheme, if you want to change i3 bar's look modify it manually based on your new scheme.

I use suckless st as my terminal, but usually just pick [Luke Smith's fork](https://github.com/LukeSmithxyz/st), which integrates many patches that otherwise I have to apply manually. [This one](https://st.suckless.org/patches/xresources/) is important for easy pywal color scheme integration.

For a quick "pop-up" browser I'm using suckless [surf](https://surf.suckless.org/), with [this patch](https://surf.suckless.org/patches/spacesearch/), which allows me to quickly search for something with $mod + s shortcut. This really helps me on my daily workflow.

### nvim

My setup uses [plugged](https://github.com/junegunn/vim-plug) for plugin management. It has a onedark theme as well as [pywal color scheme integration](https://github.com/dylanaraps/pywal) (if you want to use it, but I usually prefer to stick with onedark).

Furthermore, and more important, it uses [vim-go](https://github.com/fatih/vim-go), and [coc](https://github.com/neoclide/coc.nvim) for Language Server support, which together makes for a very good golang development environment.

It also has Rust support with it's [official plugin](https://github.com/rust-lang/rust.vim) as well as it's language server integration with coc.
