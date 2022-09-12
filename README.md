toxin (termux)
============

## Overview
A simple tool written in bash for making the process of embedding payload inside apk more easier in termux. The tool might be inspired from various tools available on web. This tool will make your life easier for embedding payload inside apk as it will install metasploit if you haven't already. Also it will download all dependencies, so it will be less pain for you.

## How to get started 
### Do basic setup for termux.
```
termux-setup-storage
pkg upgrade && pkg update
pkg install curl
```
### Next download and run tool.
```
curl -s https://raw.githubusercontent.com/noobyysauraj/toxin/master/toxin -o toxin
chmod +x toxin
./toxin
```
### Usage
![Usage Image](https://github.com/noobyysauraj/toxin/blob/master/images/usage.jpg?raw=true)
`[NOTE] Once tools installed, run setup first.`

### Use at your own responsibilities.
The author does not hold any responsibility for the bad use of this tool, this tool is made only for education purpose. Remember, with great power comes great responsibility. Please Don't be Evil.
### Tool By @Ksauraj (@noobyysauraj)