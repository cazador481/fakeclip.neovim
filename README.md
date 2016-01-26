This is a provider for an the clipboard, with support for X and tmux  
This works for windows, and mac systems.

If you are running in X
The + and * register will map to the X clipboards

If you are running w/o X and with tmux the + and * registers will map to the tmux clipboard 

to enable tmux to be mapped to the + register enable 
```
let g:vim_fakeclip_tmux_plus=1 
```

