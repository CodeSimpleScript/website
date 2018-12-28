## Description
When used, it will copy a file on the file system. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### file
Path and file name of a file to be affected by the function. File path is relative to the set web folder starting with a forward slash /.

### file
Path and file name of the new file. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return TRUE or FALSE after run.

## Examples

### Normal
	s.file_copy("/file_old.txt","/file_new.txt")
