# Alacritty

To use my config file
```
git clone https://github.com/awesomeDev12/alacritty.git ~/.config/alacritty
```
To use alacritty-themes
```
# We use Alacritty's default Linux config directory as our storage location here.
mkdir -p ~/.config/alacritty/themes
git clone https://github.com/alacritty/alacritty-theme ~/.config/alacritty/themes

# Add this as submodule
cd ~/.config/alacritty
git submodule add https://github.com/alacritty/alacritty-theme themes
```

Install alacritty on arch-linux
```
pacman -sS alacritty
sudo pacman -S alacritty
```
