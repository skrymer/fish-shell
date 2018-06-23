# fish-shell
fish shell stuff

*append to the fish user path ($fish_user_paths)
set -U fish_user_paths /path/to/add  $fish_user_paths

*set env variables 
vim ~/.config/fish/config.fish

then set -x MY_VAR my_var

echo MY_VAR -> my_var
