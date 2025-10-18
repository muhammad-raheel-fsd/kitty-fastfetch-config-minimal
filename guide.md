# Fastfetch configuration guide

1- install fastfetch

```bash
    yay -S fastfetch
```

or

```bash
    pacman -S fastfetch
```

2- create config.jsonc file

```bash
sudo nano .config/fastfetch/config.jsonc
```

3- paste [config.jsonc](config.jsonc) content in it

4- update ~/.bashrc file and paste following command at the end of file

```bash
sudo nano ~/.bashrc
```

```bash
fastfetch --config ~/.config/fastfetch/config.jsonc
```

5- you are good to go :)

# Kitty configuration guide

1- install kitty

```bash
yay -S kitty
```

or

```bash
pacman -S kitty
```

2- paste [kitty.conf](kitty.conf) in .config/kitty/kitty.conf

```bash
nano .config/kitty/kitty.conf
```
