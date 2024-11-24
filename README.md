<p align="center">
  <a href="#gh-dark-mode-only" target="_blank" rel="noopener noreferrer">
    <img src=".github/assets/night.svg" alt="adonisjs.plugin.zsh">
  </a>

  <a href="#gh-light-mode-only" target="_blank" rel="noopener noreferrer">
    <img src=".github/assets/day.svg" alt="adonisjs.plugin.zsh">
  </a>
</p>

Plugin for skipping the `node` part from the `ace` command.

## Preview

![](.github/assets/preview.gif)

## Installation

### Using Oh-My-Zsh

```bash
git clone https://github.com/baliestri/adonisjs.plugin.zsh.git $ZSH_CUSTOM/plugins/adonisjs
```

```bash
~/.zshrc
plugins=(... adonisjs)
```

### Using Zinit

```bash
zinit light baliestri/adonisjs.plugin.zsh
```

### Using Zi

```bash
zi light baliestri/adonisjs.plugin.zsh
```

### Using Zgenom

```bash
zgenom load baliestri/adonisjs.plugin.zsh
```

## Usage

```bash
cd /path/to/adonisjs/project # or subdirectory
ace # instead of node ace
```
