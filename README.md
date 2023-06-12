# mysh
some personal shell scripts for personal use

## Content
- d2m
- is\_model
- rn1
- rn2
- rn3
- rn4

## help info
- d2m 
```
set files' createdate the same as modifydate (for macOS only)
```
- $is\_model -h
```
is_model - check photos under a directory if is produced by MODEL
++ the query is based on exiftool ++
 
usage: is_model [options] MODEL [NDIR [DIRECTORY]]
 
options:
-h, --help                show brief help
-g, --tag                 specify TAG instead of 'Model'
-q                        query only; otherwise move to NDIR (default same as 
                          TAG; make it if not exist) under DIRECTORY (default 
                          CURRENT)
```
- $rn1 -h
```
rn1 - rename files sequentially under a directory
++ rn4 may required for no-simulation mode! ++
 
usage: rn1 [options] [DIRECTORY]
 
options:
-h, --help                show brief help
-x, --ext=EXT             only applied for files with this extention; default all
-p, --prefix=PREFIX       PREFIX_XXXX.EXT; default name of targit directory
-i, --ini=INI             basement for increament; default 0
-s                        simulation mode (not executed)
-v                        verbose mode
```
- $rn2 -h
```
rn2 - replace STR0 in filenames by STR1 under a directory
 
usage: rn2 [options] STR0 [STR1]
 
options:
-h, --help                show brief help
-d                        specify a path; otherwise applied to current directory!
-s                        simulation mode (not executed)
-v                        verbose mode
```
- $rn3 -h
```
rn3 - change extension case in filename(s) under a directory
 
usage: rn3 [options] [DIRECTORY]
 
options:
-h, --help                show brief help
-x, --ext=EXT             only applied for files with this extention
-u                        to uppercase; otherwise to lowercase
-s                        simulation mode (not executed)
-v                        verbose mode
```
- $rn4 -h
```
rn4 - add .x before extension in filename(s)
 
usage: rn4 [options] [DIRECTORY]
 
options:
-h, --help                show brief help
-x, --ext=EXT             only applied for files with this extention
-s                        simulation mode (not executed)
-v                        verbose mode
```
