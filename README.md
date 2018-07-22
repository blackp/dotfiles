# Philip's dotfiles

Used in conjunction with [stripysock/dotfiles](http://github.com/stripysock/dotfiles).

## Installation

```sh
brew tap thoughtbot/formulae
brew install rcm

git clone https://github.com/stripysock/dotfiles.git ~/.dotfiles-stripysock
git clone https://github.com/blackp/dotfiles.git ~/.dotfiles-personal

rcup -d ~/.dotfiles-personal ~/.dotfiles-stripysock  -x README.md -x LICENSE
```

## Credits

Thanks to Tim Riley for sharing [his dotfiles](https://github.com/timriley/dotfiles), which formed the basis of these.

Thanks to Zach Holman for sharing [his](https://github.com/holman/dotfiles).
Thanks to Thoughtbot for [their dotfiles](https://github.com/thoughtbot/dotfiles) and [rcm](https://github.com/thoughtbot/rcm).
