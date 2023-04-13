toxin (termux)
============
>Now easliy generate and embed payload inside apk with termux.

## Overview
A simple tool written in bash for making the process of embedding payload inside apk less painful. This tool might be inspired from various other tools available on web. 

## WHY ?
Embedding payload inside apk with termux was very painful earlier. So, this tool will make your life easier for embedding payload inside apk. Also it will install metasploit if you haven't already. Also it will download all dependencies for you. 

## How to get started 
### Do basic setup for termux.
```
termux-setup-storage
pkg upgrade && pkg update
pkg install curl
```
### Next download and run tool.
```
rm toxin > /dev/null 2>&1 && rm $PREFIX/bin/toxin > /dev/null 2>&1 #clean pre existing sruffs.
curl -s https://raw.githubusercontent.com/ksauraj/toxin/master/toxin -o toxin
mv toxin $PREFIX/bin 
chmod +x $PREFIX/bin/toxin
toxin
```
### Usage
![Usage Image](https://github.com/ksauraj/toxin/blob/master/images/usage.jpg?raw=true)
>[NOTE] Once tool installed, run setup first by selecting 3rd option

### Use at your own responsibilities.
The author does not hold any responsibility for the bad use of this tool, this tool is made only for educational purpose. Remember, with great power comes great responsibility. Please Don't be Evil.

>Tool By @Ksauraj
