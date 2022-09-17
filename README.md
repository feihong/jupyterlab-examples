# Feihong's JupyterLab Examples

## Prerequisites

### Install pyenv

Linux

    curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash
    # Update ~/.profile and ~/.bashrc according to instructions, then logout and login

Mac

    brew update
    brew install pyenv
    echo 'eval "$(pyenv init --path)"' >> ~/.zprofile
    echo 'eval "$(pyenv init -)"' >> ~/.zshrc

### Install latest version of Python 3

    pyenv install --list # list all versions you can install
    pyenv install 3.10.2
    pyenv global 3.10.2

# Installation

    make install

## Commands

Launch JupyterLab

    make start

## Links

- [How to use JupyterLab](https://youtu.be/A5YyoCKxEOU)
- [Source code for Pandas in Action](https://github.com/paskhaver/pandas-in-action)
- [Master Math by Coding in Python](https://learning.oreilly.com/videos/master-math-by/9781801074537/)
