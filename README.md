# My .Dotfiles

## Introduction
Welcome to my dotfiles repository! This collection contains configuration files for various tools and applications to help streamline my development environment.

## How to Install

Clone the repository into your home directory by running the following command:

```shell
git clone https://github.com/Evanalsadik/.dotfiles.git ~/.$HOME
```

Next, create aliases for specific dotfiles, such as `.tmux.conf`, `.config`, and more.

### For Tmux Files

```shell
ln -sf ~/.dotfiles/tmux/.tmux-themepack ~/.tmux-themepack
ln -sf ~/.dotfiles/tmux/.tmux.conf ~/.tmux.conf
ln -sf ~/.dotfiles/tmux/tmux ~/tmux
```

### For .Config Files

```shell
ln -sf ~/.dotfiles/.config ~/.config
```

## Usage
Feel free to explore and customize these dotfiles to suit your preferences. If you have any questions or suggestions, don't hesitate to reach out.

## Contributions
Contributions are welcome! If you'd like to contribute or provide feedback, please create an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE.md).

Thank you for exploring my dotfiles! Happy coding!
