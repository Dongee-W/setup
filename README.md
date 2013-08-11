setup.git
=========
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/sctech/setup.git
./setup/setup.sh
```

if needed:
```sh
sudo apt-get install -y byobu
```
optional:
add "(normal-erase-is-backspace-mode 0)" to "~/.emacs.d/init.el" file to enable backspace delete in emacs

See also http://github.com/startup-class/dotfiles and
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
for more details.





