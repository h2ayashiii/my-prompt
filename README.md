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
Copy config file to `~/.config/starship.toml`:
```sh
mkdir -p ~/.config && cd ~/.config
cp -n ./config_template/starship.toml ~/.config/
```
