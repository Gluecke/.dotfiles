## Steps to bootstrap a new Linux

1. Clone repo into new hidden directory.

2. Create symlinks in the Home directory to the real files in the repo.

    ```bash
    # There are better and less manual ways to do this;
    # investigate install scripts and bootstrapping tools.

    ln -s ~/.dotfiles/.bashrc ~/.bashrc
    ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
```
