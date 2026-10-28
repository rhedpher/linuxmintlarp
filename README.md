# Linux Mint Larp
- Jetbrains nerd mono font install
```
sudo apt install -y wget unzip fontconfig && mkdir -p ~/.local/share/fonts/JetBrainsMonoNF && cd /tmp && wget https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip && unzip -o JetBrainsMono.zip -d ~/.local/share/fonts/JetBrainsMonoNF && fc-cache -fv
```

- Fastfetch Install
```
sudo apt install -y software-properties-common
sudo add-apt-repository ppa:zhangsongcui3371/fastfetch
sudo apt update
sudo apt install fastfetch
```
(fastfetch config is uploaded here, and located at ~/.config/fastfetch/fastfetch.conf on your machine)

- Btop install

```
sudo apt install btop
```
