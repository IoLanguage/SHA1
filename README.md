# SHA1 
An object for calculating SHA1 hashes. Each hash calculation 
should instantiate its own SHA1 instance.

Example:
```Io
digest := SHA1 clone
digest appendSeq("this is a message")
out := digest sha1String
```
# Installation
```
eerie install https://github.com/IoLanguage/SHA1.git
```
