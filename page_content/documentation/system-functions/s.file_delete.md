## Description
When used, it will delete the file given. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### file
Path and file name of a file to be affected by the function. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return TRUE or FALSE after run.

## Examples

### Normal
	s.file_delete("/oldfile.txt")
