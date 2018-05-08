# tmuxconf
my tmuxconf
Install tmux and tpm
```
sudo apt-get install tmux xsel
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
Make a symlink between the tmuxconf/.tmux.conf and ~/.tmux.conf
```
git clone https://github.com/virgileNeu/tmuxconf.git
ln -s tmuxconf/.tmux.conf ~/.tmux.conf
```
Run tmux and launch tpm install by pressing
```
ctrl-a I
```
