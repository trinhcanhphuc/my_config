
# NEOVIM
## SET UP INSTRUCTION

### Install Neovim
Follow homepage: https://neovim.io/

### Install Vim Plugin Manager
Follow page: https://github.com/junegunn/vim-plug

### Copy all config to system folder
Use command
$ sudo cp nvim/ ~/.config/nvim

### Run install
Run commands
$ nvim .
In Neovim environment install plugins
> :PlugInstall

## Like and use it

# GIT
## Set up instruction

### Install git
Follow homepage: https://git-scm.com/

### Copy all config to system folder
$ sudo cp .gitconfig ~/.gitconfig

## Like and use it

# ANDROID STUDIO
## Set up instruction
### Download Android studio
Get from: https://developer.android.com/studio

### Extract android studio
$ sudo tar -zxvf android-studio-ide-192.6392135-linux.tar.gz -C /opt/

### Install necessary libraries
$ sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386

$ sudo adduser phuctc kvm

$ sudo chown phuctc /dev/kvm

### Run and test


## Like and use it


# BAT
## Set up instruction
Get file from release page
https://github.com/sharkdp/bat/releases
Example:
wget https://github.com/sharkdp/bat/releases/download/v0.15.4/bat_0.15.4_amd64.deb

Install:
sudo dpkg -i bat_….deb

## Like and use it


# LAZYGIT
## Set up instruction
$ sudo apt-app-repository ppa:lazygit-team/release
$ sudo apt-get update
$ sudo apt-get isntall lazygit

## Like and use it


# GITHUB
# Show all public repositories
$ curl -s https://api.github.com/users/trinhcanhphuc/repos | grep 'clone_url'


# NODEJS
## Set up instruction
$ curl -sL https://deb.nodesource.com/setup_13.x | sudo bash -
$ sudo apt-get install -y nodejs

## Like and use it
$ node -v

