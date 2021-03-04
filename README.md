# 📝 Complete `zsh` & `oh my zsh` Installation Guide

![](https://repository-images.githubusercontent.com/291137/fb009080-6110-11e9-82c2-b21ca7831f5c)

1. Installing the `zsh` Terminal:
```
sudo apt install zsh
```
2. Change default "bash" to newly installed `zsh`:
```
chsh -s $(which zsh)
```

3. Restart your device and close all the previously opened terminals (if any is on up running)

4. Open your terminal and type `2` to choose it and start `zsh`

5. Install `oh my zsh`
```
// Using curl
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

// Using wget
sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```

6. Make sure to be in `/home` directory (you can restart / open a new terminal)
```
// Using nano
sudo nano .zshrc

// Using vim
sudo vim .zshrc
```

7. Find `ZSH_THEME=` and change the assigned theme name to any you would like to change from the list -> [Themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes) and save the file

8. To apply the changes
```
source ~/.zshrc
```

Note: After changing the theme names in the file, make sure to type `source ~/.zshrc` every time to apply the changes.

## Themes
-> [Themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)



<p align="center">
	<img src="https://camo.githubusercontent.com/3ec75cb1c3278cce3c661d3bcf72a4eca75db241a6ace648ea014b02f3f44458/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6f686d797a73682f6f682d6d792d7a73682d6c6f676f2e706e67" />
</p>
