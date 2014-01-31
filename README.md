Dotfiler: config and wrapper for Tmux
=====================================

This repository contains [Tmux][] config and smart python wrapper.
It's purpose to be used as a repository for [dotfiler][].

For convinience, don't copy these files into you homedir. Instead,
go and install [dotfiler][], then clone this repository, using
`dot add <url>` command and run `dot update` to make all necessary
symlinks.

Why do I need wrapper?
----------------------

This wrapper (tmuxa) is smart enough to be able to figure out is there is
already attached client to the gieven session. Also, it has separate
command `latest`, to connect to the last used tmux session. The `latest`
command is useful, when you want to autostart tmux after the first ssh
connection to the server. That is just what `.zsh/tmux` does.

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/svetlyak40wt/dot-tmux/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

[dotfiler]: https://github.com/svetlyak40wt/dotfiler