# Oh My Posh Configuration with Git bash

## Installation

### Install Oh My Posh

```
winget install JanDeDobbeleer.OhMyPosh -s winget
```

### Install a Nerd Font

I use [Fira Code Nerd Font](https://www.nerdfonts.com/font-downloads) but you can use any other Nerd Font.

<!-- create file on root .bashrc -->

### Create a .bashrc file on root

```bash
touch ~/.bashrc
```

### Add the following lines to the .bashrc file

```bash
eval "$(oh-my-posh init bash --config https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/craver.omp.json)"
```

### Once added, reload your profile for the changes to take effect

```bash
exec bash
```
