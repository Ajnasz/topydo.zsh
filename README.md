# Topydo ZSH completion

ZSH completion rules for [topydo todo list application](https://github.com/topydo/topydo).

## Installation

### Install for plain zsh

Clone the source (or just copy the `_topydo` file):
```sh
git clone https://github.com/Ajnasz/topydo.zsh $HOME/src/topydo
```

Edit your `.zshrc` and add the path to `fpath`:

```
fpath+=$HOME/src/topydo
```

### Install to oh-my-zsh

Put/clone the plugin into your $ZSH_CUSTOM/plugins folder ($HOME/.oh-my-zsh/custom/plugins by default). Add the `topdo` plugin to the plugins list in your zshrc.
```
plugins=(topydo)
```
