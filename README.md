# dotfiles

## I3

- To Run:
~~~
sudo apt install i3 -y
sudo apt install rofi -y
sudo apt install feh -y
sudo apt install compton -y

cp dotfiles/.i3/config ~/.config/i3/config
cp dotfiles/i3blocs.conf ~
~~~
- Useful snippets
  - Identifying window class to bind to a workspace
~~~
xprop | grep WM_CLASS | awk '{ print $4 }'
~~~

# Zsh

- Install `zsh`
- Install `oh-my-zsh`
- Install power line fonts 
 ```
git clone https://github.com/powerline/fonts.git # Clone the github repo
cd fonts    # Change to the cloned repos directory
./install.sh    # Run the install script
sudo fc-cache -fv    # Refresh the font cache, saves logging out and back in
  ```

- Plugins
 ```
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
git clone https://github.com/wting/autojump ~/.oh-my-zsh/custom/plugins/autojump
  ```
  
