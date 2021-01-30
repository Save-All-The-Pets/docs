# WSL2 Set up

1. Add the following to your `.bashrc` or `.zshrc` files.

        export PYENV_ROOT="$HOME/.pyenv"
        export PATH="$PYENV_ROOT/bin:$PATH"
        if command -v pyenv 1>/dev/null 2>&1; then
            eval "$(pyenv init -)"
        fi

2. Run `linux_package_instal.sh` to install necessary linux packages.
