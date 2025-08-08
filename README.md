Dotfiles
=================

This is my repository for tracking my own dotfiles with [Dotbot](https://github.com/anishathalye/dotbot). I heavily referenced Anish Arhalye's [Managing You Dotfiles](https://anishathalye.com/managing-your-dotfiles/#user-content-fn-3) to create this repo.

In general, the idea is to use symbolic links for everything, and using git
submodules whenever possible, 
See [anishathalye](anishathalye) (creator of the [template](https://github.com/anishathalye/dotfiles_template) this repo was created from and [dotbot](https://github.com/anishathalye/dotbot)).
To create a symbolic link: `ln -s /path/to/original /path/to/link`

To keep submodules at their proper versions, you could include something like
`git submodule update --init --recursive` in your `install.conf.yaml`.

To upgrade your submodules to their latest versions, you could periodically run
`git submodule update --init --remote`.


License
-------

This software is hereby released into the public domain. That means you can do
whatever you want with it without restriction. See `LICENSE.md` for details.
