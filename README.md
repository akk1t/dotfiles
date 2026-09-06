# dotfiles

My personal dotfiles.

## Setup

### 1. Install Homebrew

Install [Homebrew](https://brew.sh/) if you don't have it installed yet.

After installation, make sure `brew` is available:

```sh
brew --version
```

### 2. Install Ghostty

Install [Ghostty](https://ghostty.org/):

```sh
brew install --cask ghostty
```

### 3. Install GitHub CLI

Install `gh`:

```sh
brew install gh
```

Authenticate with GitHub:

```sh
gh auth login
```

Check the authentication status:

```sh
gh auth status
```

### 4. Install delta

Install [delta](https://github.com/dandavison/delta):

```sh
brew install git-delta
```

### 5. Install Neovim

This setup uses [akk1t/kickstart.nvim](https://github.com/akk1t/kickstart.nvim) as the Neovim configuration.

Install Neovim and its dependencies:

```sh
brew install neovim ripgrep fd tree-sitter
```

Clone the configuration:

```sh
git clone https://github.com/akk1t/kickstart.nvim.git ~/.config/nvim
```

Start Neovim:

```sh
nvim
```

On the first launch, Neovim will install the plugins defined in the configuration.

## Setup Summary

1. Install Homebrew
2. Install Ghostty
3. Install GitHub CLI (`gh`)
4. Authenticate with GitHub using `gh auth login`
5. Install `delta`
6. Install Neovim and its dependencies
7. Clone `akk1t/kickstart.nvim` to `~/.config/nvim`
8. Launch Neovim with `nvim`

