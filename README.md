Pictime
=======

http://github.com/heldercorreia/pictime

Recursive photo renamer based on **EXIF Date and Time**. The program consists of a
single Bash script. Tested on Linux only, but should work on every platform
supported by _exif_ and _Bash_.

For usage help, run:

> pictime -h

_Pictime_ renames all files with extension **jpg**, **jpeg**, **JPG** and **JPEG** that
contain a valid date and time EXIF record. The new name will have the format
**yyyymmddhhmmss**._jpg_. Optionally, the program can find and act upon all photos
in all subdirectories. By default, it looks in the current directory only. **Warning**: the renaming operation always overwrites.

### Requirements ###

 - _exif_ and _libexif_ (http://libexif.sourceforge.net/) - on Ubuntu, simply install the
 _exif_ package.
 - _GNU bash_ (version 4.2.x) - should be installed by default on Ubuntu.