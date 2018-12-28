## Description
Will change the name of a file. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### file
Path and file name of a file to be found. File path is relative to the set web folder starting with a forward slash /.

### file
Path and file name that the current file will be changed to. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return TRUE if worked, FALSE if it did not.

## Examples

### Normal
	s.file_rename("/file.txt","/newname.txt")
