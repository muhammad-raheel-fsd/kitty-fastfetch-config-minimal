**# Before starting conf make sure you are in root directory**

```bash
cd ~
```

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
sudo sudo nano .config/fastfetch/config.jsonc
```

3- paste [config.jsonc](config.jsonc) content in it

4- update ~/.bashrc file and paste following command at the end of file

```bash
sudo sudo nano ~/.bashrc
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
sudo nano .config/kitty/kitty.conf
```

# Starship prompt configuration

1- Install starship

```bash
yay -S starship
```

2- create config file

```bash
sudo nano .config/startship.toml
```

3- Paste the contents of [Starship Toml File](./starship.toml) in it

4- Update ~/.bashrc to initate it - Add the following line in the end of file

```bash
eval "$(starship init bash)"
```

```bash
sudo nano ~/.bashrc
```
