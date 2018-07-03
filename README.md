# fish-shell
fish shell stuff

__set fish as your default shell__ 

chsh -s 'which fish' 

__append to the fish user path ($fish_user_paths)__

set -U fish_user_paths /path/to/add  $fish_user_paths

__set env variables__ 
* vim ~/.config/fish/config.fish
* then set -x MY_VAR my_var
* echo MY_VAR -> my_var

example:

set -x NODE_HOME /home/skrymer/coding/node/node-v8.11.3-linux-x64
set -x JAVA_HOME /home/skrymer/coding/java/jdk1.8.0_172
set -x GRADLE_HOME /home/skrymer/coding/gradle/gradle-4.8-rc-3
set -x MAVEN_HOME /home/skrymer/coding/maven/apache-maven-3.5.4

