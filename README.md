A tool to find and edit your rc files

### Problem

Many CLI applications use a text file to store their configurations. Often called an rc file or dotfile. The problem is that the name varies per application. The SSH client stores configs in `~/.ssh/config`, but ZSH uses `~/.zshrc`. These are just the user level configs, other applications can have directory based rc files. Like `.npmrc`
