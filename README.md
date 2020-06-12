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
