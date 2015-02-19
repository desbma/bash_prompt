Bash prompt
===========

This is my custom Bash prompt.


## Features

* Display status of last command with emphasis on error if any
* Display Bash history command #, time, user and hostname
* Display current working directory in dedicated line
* Display number of Bash jobs running in the background, if any
* Make it obvious when you are root
* Make it obvious when you are connected through SSH
* Degrades gracefully when no color support is available
* Compatible with [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt)
* Looks great :)


## Screenshots

Standard prompt on ~:  
![prompt](http://i.imgur.com/YW5tAiJ.png)

Standard prompt on /some/directory:  
![prompt](http://i.imgur.com/q2pZYUT.png)

Prompt on ~, running as root:  
![prompt](http://i.imgur.com/3Th47aX.png)

Prompt on ~, running as root, connected to _remote_hostname_ through SSH:  
![prompt](http://i.imgur.com/8vwCYIO.png)

Prompt on ~, when last command returned code 1:  
![prompt](http://i.imgur.com/ziK72i5.png)

Prompt on ~, when last command returned code 127:  
![prompt](http://i.imgur.com/gKSGb8A.png)

Prompt on ~, when last command was interrupted with _CTRL+C_:  
![prompt](http://i.imgur.com/jXbOha7.png)

Prompt on ~, when last command was killed:  
![prompt](http://i.imgur.com/lAJRkDq.png)

Prompt on a repository on /some/directory with [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt):  
![prompt](http://i.imgur.com/yIcCBGg.png)

Prompt on ~, with 1 background Bash job:  
![prompt](http://i.imgur.com/KHX4HHB.png)


## Installation

1. Download it to your home directory, ie with:   
`curl https://raw.githubusercontent.com/desbma/bash_prompt/master/prompt > ~/bash_prompt`

2. Edit `~/.bashrc` and replace prompt code by:  
`. ~/bash_prompt` 


## License

[GPLv3](https://www.gnu.org/licenses/gpl-3.0-standalone.html)
