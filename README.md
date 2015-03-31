dot-bookmarks
===

Easily bookmark commonly used directories.

to install, copy the .bookmarks script to your home directory
and add this line to .bashrc or .zshrc:
```
    source ~/.bookmarks
```

to bookmark the current directory using name "blah":
```
    mark blah
```

to change to a directory bookmarked as "blah":
```
    @blah
```
to get a directory name as a variable, use:
```
    $_blah
```
example:
```
    mv file $_blah
```

to remove a bookmark, remove them from the end of the .bookmarks file
