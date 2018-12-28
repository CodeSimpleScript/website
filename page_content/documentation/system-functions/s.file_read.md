## Description
Will return the content of a file. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### file
Path and file name of a file to be read. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return content from the file, and FALSE if file loading fails.

## Examples

### Normal
	v.content=s.file_read("/file.txt")
