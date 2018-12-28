## Description
Will return if it can locate a file on the file system. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### file
Path and file name of a file to be found. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return TRUE if file is found, or FALSE.

## Examples

### Normal
	v.filefound=s.file_exists("/file.txt")
