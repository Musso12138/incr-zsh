forked from http://mimosa-pudica.net/zsh-incremental.html

incr is a really great plugin for oh-my-zsh. But the incremental completion of incr is **automatic** and **always on**. I tried to compile hello.c to executable file hello. But hello is always autocompleted to hello.c since hello.c is the only file in the dir. It is annoying.

This repository has commented out the line of code `show-prediction` within the `vi-backward-delete-char-incr` and `backward-delete-char-incr` function. And you can temporarily disable incr after pressing backspace.

## Installation

Clone the repository:

```
git clone git@github.com:Musso12138/incr.plugin.zsh
```

Create directory for incr plugin:

```
mkdir ~/.oh-my-zsh/plugins/incr
```

Move incr.plugin.zsh to the directory:

```
mv incr.plugin.zsh/incr.plugin.zsh ~/.on-my-zsh/plugins/incr
```

Load incr plugin:

```
source ~/.on-my-zsh/plugins/incr/incr*.zsh
```



