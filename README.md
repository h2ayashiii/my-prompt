# my-prompt
for personal use.

# Usage
## Install starship
```sh
curl -sS https://starship.rs/install.sh | sh
```

- for MacOS
    ```sh
    brew install starship
    ```

- for Conda
    ```sh
    conda install -c conda-forge starship
    ```

## Install fonts
Recommended font:
- [Nerd Font](https://www.nerdfonts.com/font-downloads)
    - Hack Nerd Font

### Install fonts to OS
- MacOS
    - Set by `Font Book.app`.
- Windows
    - Set by `Settings > Personalization > Font`.

### Adapting fonts to Vscode
- Open VScode Settings.
- Search: `Font Family`.
- Enter `Hack Nerd Font` in the `Font Family` box.

## Setup to shell
- Bash  
    Add the following to the end of `~/.bashrc`:
    ```sh
    eval "$(starship init bash)"
    ```
- Zsh  
    Add the following to the end of `~/.zshrc`:
    ```sh
    eval "$(starship init zsh)"
    ```

## Configuration
See: https://starship.rs/ja-JP/config/

- My configuration:  
    Copy config file to `~/.config/starship.toml`:
    ```sh
    mkdir -p ~/.config && cd ~/.config
    cp -n ./config_template/starship.toml ~/.config/
    ```
