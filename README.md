# New Laptop Setup

A script to set up an macOS laptop for web and mobile development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

## Install

Download the script:

```sh
curl --remote-name https://raw.githubusercontent.com/guusli/new-laptop/master/mac
```

Review the script (avoid running scripts you haven't read!):

```sh
less mac
```

Execute the downloaded script:

```sh
sh mac 2>&1 | tee ~/laptop.log
```

## Debugging

Your last Laptop run will be saved to `~/laptop.log`.

## What it sets up

macOS tools:

* [Homebrew] for managing operating system libraries.

[homebrew]: http://brew.sh/

Unix tools:

* [Antibody] for handling zsh packages
* [Autojump] for easy navigation from the command line
* [DiffSoFancy] for better git diffs
* [Git] for version control
* [OpenSSL] for Transport Layer Security (TLS)
* [The Silver Searcher] for finding things in files
* [Watchman] for watching for filesystem events
* [YADM] for version controlling dotfiles
* [Zsh] as your shell
* [vim-plug] for managing vim plugins

[git]: https://git-scm.com/
[openssl]: https://www.openssl.org/
[the silver searcher]: https://github.com/ggreer/the_silver_searcher
[watchman]: https://facebook.github.io/watchman/
[zsh]: http://www.zsh.org/
[heroku cli]: https://devcenter.heroku.com/articles/heroku-cli
[yadm]: https://github.com/TheLocehiliosan/yadm
[antibody]: https://getantibody.github.io/
[autojump]: https://github.com/wting/autojump
[vim-plug]: https://github.com/junegunn/vim-plug
[diffsofancy]: https://github.com/so-fancy/diff-so-fancy

GitHub tools:

* [Hub] for interacting with the GitHub API

[hub]: http://hub.github.com/

Image tools:

* [ImageMagick] for cropping and resizing images

Programming languages, package managers, and configuration:

* [Node.js] and [NPM], for running apps and installing JavaScript packages
* [NVM] for managing node versions
* [rbenv] for managing ruby versions
* [Ruby] stable for writing general-purpose code
* [Yarn] for managing JavaScript packages

[imagemagick]: http://www.imagemagick.org/
[node.js]: http://nodejs.org/
[npm]: https://www.npmjs.org/
[asdf]: https://github.com/asdf-vm/asdf
[ruby]: https://www.ruby-lang.org/en/
[yarn]: https://yarnpkg.com/en/
[nvm]: https://github.com/creationix/nvm
[rbenv]: https://github.com/rbenv/rbenv

Databases:

* [Postgres] for storing relational data
* [Redis] for storing key-value data

[postgres]: http://www.postgresql.org/
[redis]: http://redis.io/

Mac apps:

* [Iterm2] A terminal replacement
* [Spotify] For listening to music
* [Spectacle] For managing windows
* [Atom] A code editor
* [Alfred] A productivity app
* [1Password] A password manager

[iterm2]: https://www.iterm2.com/
[spotify]: https://www.spotify.com/
[spectacle]: https://www.spectacleapp.com/
[atom]: https://atom.io/
[alfred]: https://www.alfredapp.com/
[1password]: https://1password.com/
