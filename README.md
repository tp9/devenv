Fetch and link to config files
==============================
git clone https://github.com/wokumura/devenv.git

ln -sb devenv/.tmux.conf ~

ln -sb devenv/.bash_profile ~

ln -sb devenv/.bashrc ~

ln -sb devenv/.bashrc_custom ~

ln -sb devenv/.gitconfig ~

ln -sb devenv/.jshintrc ~

ln -sd .vim devenv/.vim 


Install rlwrap. Required for node in tmux
=========================================
sudo apt-get install -y rlwrap

Install node
============
sudo apt-get install -y nodejs
