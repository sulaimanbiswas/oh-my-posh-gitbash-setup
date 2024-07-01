# Oh My Posh Configuration with Git bash

## Installation

### Install Oh My Posh

```
winget install JanDeDobbeleer.OhMyPosh -s winget
```

### Install a Nerd Font

I use [Fira Code Nerd Font](https://www.nerdfonts.com/font-downloads) but you can use any other Nerd Font.

### Create a .bashrc file on root

```bash
touch ~/.bashrc
```

### Add the following lines to the .bashrc file

```bash
eval "$(oh-my-posh init bash --config https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/craver.omp.json)"
```

### Change the theme to your liking

You can change the theme by changing the `craver.omp.json` to any other theme you like. You can find the themes [here](https://ohmyposh.dev/docs/themes)

### Add the following lines to the .bash_profile file

```bash

if [ -f ~/.bashrc ]; then
   source ~/.bashrc
fi
```

### Once added, reload your profile for the changes to take effect

```bash
exec bash
```
