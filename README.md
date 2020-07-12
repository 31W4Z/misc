# Misc


-Python TTY Shell-
python -c 'import pty; pty.spawn("/bin/bash")'
export TERM=screen-256color
[Ctrl Z]
echo $TERM
stty raw -echo
fg
[INTRO]
export TERM=screen
