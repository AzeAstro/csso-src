# CSSO(Counter Strike Source Offensive)
This mod is only for CSS v91 and above(doesn't work on v34)  
## NOT SUCCEEDED YET!
## Requirements for compiling for Linux
1) Perforce(aka P4)
2) Linux (Ubuntu/Debian based for now. I hate to Arch,sorry.)
3) Python3
## Installation
Run as **SUDO**: 
```bash
sudo ./installer
```



## Error checkpoints
This is checkpoint that I note here. If you may help feel free to write me in discord. My Discord: Running Child#1366  
Or if you have one of the problembs listed here and you can't solve then you can write me too. I will do my best to help.  
- `./createcssoproject : devtools/bin/vpc_linux: file not found` - Fixed.
- `gperftools-2.0 not found` - Fixed.
- `devtools/makefile_base_posix.mak not found` - Fixed.
- `bash: p4 command not found` - Fixed(`installer` now automatically fixes it.)
- `Perforce client error:
	Connect to server failed; check $P4PORT.
	TCP connect to perforce:1666 failed.
	Temporary failure in name resolution` - Fixed for myself but it is not in installer/script yet. I will make script for it too.
- `ccache: FATAL: /valve/steam-runtime/bin/g++: execv returned (No such file or directory)` - *Welp*
