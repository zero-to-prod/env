# Build

```bash
docker build -t dev .
```

# Rebuild
```bash
docker build . -t dev
docker build . -f nvim.Dockerfile -t dev
```

# Run

```bash
docker run --rm -it dev bash
```

# ZSH
```bash
apt install zsh
chsh -s `which zsh`
```

# oh-my-zsh
```bash
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
vim ~/.zshrc
# plugins=(git zsh-autosuggestions)
git clone https://github.com/zsh-users/zsh-autosuggestions.git ~/.oh-my-zsh/plugins/zsh-autosuggestions
```