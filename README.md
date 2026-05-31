<p align="center">
    <img src="./docs/banner.png" alt="Dotfiles Banner"/>
</p>

<p align="center">
    Personal configuration files for my development environment, focused on a clean terminal workflow with Zsh, Neovim and macOS.
</p>

<p align="center">
    <a href="#"><img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status"></a>
    <a href="#"><img src="https://img.shields.io/badge/Built%20by-Yenterick-blueviolet?style=for-the-badge" alt="Built by Yenterick"></a>
</p>

---

## Included Configurations

- iTerm2
- Zsh
  - Powerlevel10k
- Neovim
- Yazi

## Setup

Clone the repository:

```bash
git clone https://github.com/Yenterick/dotfiles.git ~/dotfiles
```

Setup iTerm2:

  iTerm2 → Settings → Profiles → Other Actions → Import JSON Profiles...

Create symlinks:

```bash
ln -s ~/dotfiles/.zshrc ~/.zshrc
ln -s ~/dotfiles/.p10k.zsh ~/.p10k.zsh
ln -s ~/dotfiles/p10k/ ~/.config/p10k
ln -s ~/dotfiles/nvim ~/.config/nvim
ln -s ~/dotfiles/yazi ~/.config/yazi
```

---

## License

This project is licensed under the MIT License.

## Author

Yenterick
