# genpasswd

## Overview
genpasswd is a tool for creating randomised strings with an assortment of characters, written in Python. Because of this, it is highly customisable, by argv options and by modifying the script itself.

### Usage
```genpasswd [length] [-ilush]```

### Options
```
-i            Exclude integers from the password
-l            Exclude lowercase letters from the password
-u            Exclude uppercase letters from the password
-s            Exclude special characters letters from the password
-h | --help   Show the help screen
```

### Examples
```
$ genpasswd
Created password 10 characters long:
Iq*QM.&dg$
```
```
$ genpasswd -i
Created password 10 characters long:
oS*Uk^S*z?
```
```
$ genpasswd 20
Created password 20 characters long:
C3Pi$3H%##nm1bNg~8S.
```
```
$ genpasswd 36 -l -s
Created password 36 characters long:
28L7UT403D6YU9PX197L036486V921HV3UQE
```
## Install
To install on most Unix-like operating systems, ensure python3 and git are installed.
- First, `git clone https://github.com/bradeythedev/Random-password-generator/` or download 'genpasswd' from a release in the releases tab.
- Open a terminal and enter the directory containing 'genpasswd' by `cd Random-password-generator/`
- Make the 'genpasswd' file executable by `chmod +x genpasswd`
- (Optional) Move the executable into a $PATH directory with `sudo cp genpasswd /usr/local/bin/` or `doas cp genpasswd /usr/local/bin/` (shoutout to BSD users)

To install on Windows, first get a better operating system- alright, fine. Install python3, download 'genpasswd' from the releases tab, and right-click open with python in file explorer (I *think*, I honestly have no idea).
