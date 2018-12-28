## Description
Will delete a folder on the file system when called. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### folder
Path and folder name of a folder to be deleted. Folder path is relative to the set web folder starting with a forward slash /.

## Return
Will return TRUE if folder is deleted, or FALSE.

## Examples

### Normal
	v.diditwork=s.folder_delete("/docs/oldcrap")
