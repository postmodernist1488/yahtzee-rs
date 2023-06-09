# Yahtzee-rs
Yahtzee game in Rust

## Controls
- Arrow keys <kbd>Up</kbd>/<kbd>Down</kbd>/<kbd>Enter</kbd> to choose die for saving
- You can also use <kbd>h</kbd><kbd>j</kbd><kbd>k</kbd><kbd>l</kbd>
- <kbd>Ctrl+C</kbd> or <kbd>Q</kbd> during the game to exit
## Features
- Ncurses TUI for playing in your favourite terminal
- Simple AI that plays against the human player
- Highscore saving (see ~/.config/highscore.txt)

## Installation
You can either build the latest version from [Github](https://github.com/postmodernist1488/yahtzee-rs.git):
```console
$ git clone https://github.com/postmodernist1488/yahtzee-rs.git
$ cd yahtzee-rs
$ cargo build --release
$ cd target/release/
$ ./yahtzee
```
or install from [crates.io](https://crates.io/crates/yahtzee):
```console
$ cargo install yahtzee
$ yahtzee
```
