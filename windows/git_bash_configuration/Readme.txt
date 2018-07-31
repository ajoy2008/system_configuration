Git-Bash
---------
C:\Program Files\Git\etc\bash.bashrc
#Added by Ajoy
export PS1='\[\e[1;32m\]\u\[\e[1;35m\]@\[\e[1;32m\]\h\[\e[1;33m\]\[\e[1;35m\]->\[\e[1;31m\]\w\[\e[1;35m\] \$ \[\e[1;33m\]'

# Uncomment to use the terminal colours set in DIR_COLORS
eval "$(dircolors -b /etc/DIR_COLORS)"

Add following in end of DIR_COLORS
#############################
# verilog files (bold cyan)
.v 01;36
.sv 01;36
.b 01;36
.vt 01;36
.fsdb 00;35

#############################
# Code files
.c 01;37   #White
.h 01;33   #Yellow
.asm 01;32 #Green
.o 01;31   #Red
.exe 01;35

#############################