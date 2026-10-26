# Linux Mint Larp
- Jetbrains nerd mono font install
```sudo apt updatesudo apt install -y curl unzipmkdir -p ~/.local/share/fonts/JetBrainsMonocurl -fLo /tmp/JetBrainsMono.zip \  https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zipunzip -o /tmp/JetBrainsMono.zip -d ~/.local/share/fonts/JetBrainsMonofc-cache -f```

- Fastfetch Install
```sudo apt install -y software-properties-common
sudo add-apt-repository ppa:zhangsongcui3371/fastfetch
sudo apt update
sudo apt install fastfetch
```
(fastfetch config is uploaded here, and located at ~/.config/fastfetch/fastfetch.conf on your machine)

- Btop install
```sudo apt install btop```
