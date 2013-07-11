dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure your `bash` development environment as follows:

```sh
cd $HOME
git clone https://github.com/acorred1/dotfiles.git
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
```

See also http://github.com/startup-class/setup to install prerequisite
programs.
