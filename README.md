# cygwin-winpty
Application winpty for cygwin, downloaded from https://github.com/rprichard/winpty/releases.

# Version
  * winpty-0.4.0-cygwin-2.5.2-ia32.tar.gz - winpty compiled for 32-bit Cygwin
    https://github.com/rprichard/winpty/releases/download/0.4.0/winpty-0.4.0-cygwin-2.5.2-ia32.tar.gz
  * winpty-0.4.0-cygwin-2.5.2-x64.tar.gz - winpty compiled for 64-bit Cygwin
    https://github.com/rprichard/winpty/releases/download/0.4.0/winpty-0.4.0-cygwin-2.5.2-x64.tar.gz

# Install
tar -C /bin/ --wildcards --no-anchored --strip-components=2 -zxvf winpty-0.4.0-cygwin-2.5.2-x64.tar.gz "*/bin/winpty*"

# Usage
I use this app with docker. Example, command: "winpty docker pull centos:7" - in cygwin/mintty.exe progresbar is broken. Winpty fix this.
