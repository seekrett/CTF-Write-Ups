# List of terminal commands

This file contains a list of commands that were learnt along the way, solving CTFs.

_____

`file` : determines the type of a specified file<br/>
Make it a practice to always check what kind of file is received from CTF challenges!

`grep` : searches for __PATTERNS__ in each __FILE__<br/>
`egrep [cmd line options] <pattern> [path]` : prints every line which contains a given pattern

**cmd line options:**<br/>
&nbsp;&nbsp; `-n` : know the liner number as well<br/>
&nbsp;&nbsp; `-c` : count how many lines were matched<br/>
&nbsp;&nbsp; `-r` : read all files under each directory, recursively

[more info for grep here](https://ryanstutorials.net/linuxtutorial/grep.php)

`unzip` : unzips a zip file

`find` : searches for files in a directory hierarchy

**samples:**<br/>
&nbsp;&nbsp; `find . -name thisfile.txt` : find thisfile.txt in current directory<br/>
&nbsp;&nbsp; `find /home -name *.jpg` : find any .jpg file in home dir and any subdirs in it<br/>
&nbsp;&nbsp; `find . -type f -empty` : find `-empty` files (`-type f`) in current directory<br/>
&nbsp;&nbsp; `find /home -user randomperson-mtime 6 -iname ".db"` : find `.db` files, ignoring text case (`-iname`) modified in the last 6 days (`-mtime 6`) by randomperson (`-user randomperson`)

[more info for find here](https://www.plesk.com/blog/various/find-files-in-linux-via-command-line/)
