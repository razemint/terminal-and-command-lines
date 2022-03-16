# Linux Terminal and Command Lines

Some examples of the linux terminal and command lines.

## Directories

- change directory: `cd previous/name_of_the_directory`
- to go to the previous root/directory: `cd ..`
- go home/root: `cd ~` or `cd`
- change between directories: `pushd`
- get back to previous directory `popd`
- make directory: `mkdir _name_`

## Lists

- See the items inside a direction in linux the command is:
  `ls`
- see in a detailed way: `ls -l`
- see in a detailed human way: `ls -lh`
- see in a detailed way with hidden files: `ls -lha`
- see the listing of the previous directory: `ls -lha ..`

## Working directory

- see the direction where we are working is: `pwd`
- "change" the name of the directory: `mv _actual name_ _new name_`
- move a file to another directory: `mv _file_ _route_`
- delete a directory: `rm -rf _directory_`

## Files

- make a new file: `touch _filename_`
- delete file: `rm _filename_`
- make a copy of a file and send it to a directory: `cp _filename_ _route_`
- open a file: `open _filename_` / (in some other distros) `start _filename_`
- to see a file in depth: `more _filename_` / (in some other distros) `less _filename_`
- print all the content of a file in screen: `cat _filename_`
- see the last 10 lines of a file: `tail _filename_`
- see the first 10 lines of a file: `head _filename_`
- To see the ubication of the binary archive inside the PATH: `which _command_`
- Print the enviroment variable (PATH): `echo $PATH`

## Help

- to see a manual/explanation of each command: `man _command_`
- Create a variable which stores a command: `alias _nameofthevariable_= '_command_'`
- Clean terminal: `ctrl/cmd + l`
- Search used commands: `ctrl/cmd + r`
