## Description
Will return TRUE if it can locate a folder on the file system. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### folder
Path and file name of a folder to be found. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return TRUE if file is found, or FALSE.

## Examples

### Normal
	v.found=s.folder_exists("/docs/olddocs")
