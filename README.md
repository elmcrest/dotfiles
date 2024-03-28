# dotfiles
workstation setup and dotfiles repository, use at your own risk

## macOS only
- [homebrew](https://brew.sh/)

## Fonts
[nerd-fonts](https://github.com/ryanoasis/nerd-fonts/blob/master/readme.md)
on `macOS`:
```
brew tap homebrew/cask-fonts
brew install font-hack-nerd-font
```
setup your terminals to use the font

## tools
python installation(s): [pyenv](https://github.com/pyenv/pyenv)

terminal: [warp](https://www.warp.dev/) - `brew install --cask warp`

cat replacement: [bat](https://github.com/sharkdp/bat) - `cargo install bat`

sed alternative: [sd](https://github.com/chmln/sd) - `cargo install sd`

find alternative: [fd](https://github.com/sharkdp/fd) - `brew install fd`

ls deluxe: [lsd](https://github.com/Peltoche/lsd) - `cargo install lsd`

grep alternative: [ripgrep](https://github.com/BurntSushi/ripgrep) - `cargo install ripgrep`

find and clean project artifacts: [kondo](https://github.com/tbillington/kondo) - `cargo install kondo`

print lines of code with colors: [tokei](https://github.com/XAMPPRocky/tokei) - `cargo install tokei`

make Makefile replacement just with justfile: [just](https://github.com/casey/just) - `cargo install just`


## zsh dot file
`.zshenv' is sourced on all invocations of the shell, unless the -f option is set. It should contain commands to set the command search path, plus other important environment variables. `.zshenv' should not contain commands that produce output or assume the shell is attached to a tty.

`.zshrc' is sourced in interactive shells. It should contain commands to set up aliases, functions, options, key bindings, etc.

`.zlogin' is sourced in login shells. It should contain commands that should be executed only in login shells. `.zlogout' is sourced when login shells exit. `.zprofile' is similar to `.zlogin', except that it is sourced before `.zshrc'. `.zprofile' is meant as an alternative to `.zlogin' for ksh fans; the two are not intended to be used together, although this could certainly be done if desired. `.zlogin' is not the place for alias definitions, options, environment variable settings, etc.; as a general rule, it should not change the shell environment at all. Rather, it should be used to set the terminal type and run a series of external commands (fortune, msgs, etc).
