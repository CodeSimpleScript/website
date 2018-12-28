## Description
Will return the size in bytes of a file. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### file
Path and file name of a file to be read. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return the size of the file in bytes, or FALSE if file loading fails.

## Examples

### Normal
	v.bytes=s.file_size("/file.txt")
