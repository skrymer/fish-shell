# fish-shell
fish shell stuff

__set fish as your default shell__ 
chsh -s `which fish` 

__append to the fish user path ($fish_user_paths)__
set -U fish_user_paths /path/to/add  $fish_user_paths

__set env variables__ 
* vim ~/.config/fish/config.fish
* then set -x MY_VAR my_var
* echo MY_VAR -> my_var
