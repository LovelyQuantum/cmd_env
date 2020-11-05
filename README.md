# Initial Command Line
## zsh is good, tmux is good. Let's work with them!
## How to install?

Update source
```bash
sudo apt update
```

Install zsh
```bash
sudo apt install zsh tmux
```

Install ohmyzsh
```bash
./ohmyzsh.sh
```

After finish installing above, run after command to install powerline10k and other essential components.
```bash
./install.sh
```

At last restart tmux
```bash
tmux source ~/.tmux.conf
```