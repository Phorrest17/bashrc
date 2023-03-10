# bashrc
.bashrc with notes for customization of prompt

You can modify the following line in bashrc

PS1='${debian_chroot:+($debian_chroot)}\[\033[01;34m\]\u\[\033[01;37m\]@\[\033[01;35m\]\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\$ '
In order that you are able to change the colors for the user, @ symbole, and host to delineate between hosts more easily. The data in the following line snippet is what modifies this

[\033[01;34m]\u[\033[01;37m]@[\033[01;35m]\h[\033[00m]

Use the table below to edit the entry before \u, @, and \h\

Black 0;30    Dark Gray 1;30 
Blue 0;34     Light Blue 1;34 
Green 0;32    Light Green 1;32 
Cyan 0;36     Light Cyan 
1;36 Red      0;31 Light Red 
1;31 Purple   0;35 Light Purple 
1;35 Brown    0;33 Yellow 1;33 
Light Gray    0;37 White 1;37
