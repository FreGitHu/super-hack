# Super Hack

**Table of contents**

1. [What is this *program* for](#what-is-this-program-for)
2. [How to use this *program*](#how-to-use-this-program)
3. [How to create your own vurnerabilites](#how-to-create-your-own-vurnerabilites)
    1. [The Format](#the-format)
    2. [Saving The file](#saving-the-file)
    3. [Publishing with Git](#publishing-with-git)
---
## What is this *program* for?
**This *program* is *for* educational or protecting servers**
and also teaching people that hacking can be very dangerous.
---
## How to use this *program*
The easy way to do this is run `main.py -i`
There are some syntax that you can do if you don't want to do the easy way.
```
main.py
Syntax:
-i Interative Mode
-a The ip to target
-e The exploit to use (can't use if -b is active)
-b Go through every exploit in the software
-u Update repository
```
---
## How to create your own vurnerabilites
### The Format
Create an .ini file in your /exploits folder
Here is an example:
```ini
File startcmdself.ini
[Order]
myhackvar=42
inst1=startCMD
[startCMD]
type=Run
remote=localhost
file=cmd.exe
arg1 = myhackvar
result=myhackvar
[saveToFile]
type=Save
file=data.txt
data=myhackvar
```
### Saving the file
For example notepad in windows
```
Control+S
File Type: *
File Name: [your-vurn].ini
```
### Publishing with git
First, [download Git](https://git-scm.com/downloads) then run this code in your term
```shell
mkdir mycopy
git clone 
```