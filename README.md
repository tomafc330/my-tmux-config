my-tmux-config
==============

This is my tmux config


to auto load, change in .bashrc

if [ $TERM != "screen-256color" ] && [  $TERM != "screen" ]; then
    tmux attach || tmux new -s tmux -n main; exit
fi
