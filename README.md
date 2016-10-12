# Monokai ls colors #

Monokai colors for LS_COLORS environment variable. Directory colors are left intact from the default settings (directories are still dark blue instead of fluorescent red).

Insert

	eval $( dircolors -b $LS_COLORS)

(where **$LS_COLORS** is path to *.LS_COLORS* file) to your **$HOME/*.bashrc*** to load it into the environment variable.
