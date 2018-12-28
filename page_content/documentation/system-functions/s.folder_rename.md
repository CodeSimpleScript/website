## Description
Will change the name of a folder. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.
## Parameters

### folder
Path and name of the old folder. File path is relative to the set web folder starting with a forward slash /.

### folder
Path and new folder name. File path is relitive to the set web folder starting with a forward slash /.

## Return
Will return TRUE if worked, FALSE if it did not.

## Examples

### Normal
	s.folder_rename("/backups","/backups_old")
