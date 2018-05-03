# dot-i3

## Requirements

- i3

## Manual installation

Clone and change directory

    git clone https://github.com/LEI/dot-i3.git ~/.dot/i3 && cd $_

Create the directory `~/.config/i3`

    mkdir -p "$HOME/.config/i3"

Link files to home directory

    ln -isv "~/.dot/i3/{bin,config,*.conf}" "$HOME/.config/i3"
    ln -isv "~/.dot/i3/{.Xresources.d,.wallpaper}" "$HOME"

## Resources

- [i3wm docs](https://i3wm.org/docs/)
