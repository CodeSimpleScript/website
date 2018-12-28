## Description
Will create a folder on the file system when called in the web folder. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### folder
Path and file name of a folder to be created. File path is relative to the set web folder starting with a forward slash /.

## Return
Will return TRUE if folder is created, or FALSE.

## Examples

### Normal
	s.folder_create("/docs/newdocs")
