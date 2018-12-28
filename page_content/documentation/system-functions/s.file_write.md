## Description
Will replace the content in a file with new content. This is part of the file system functions. Improper use of the file system functions can lead to loss of data.

## Parameters

### file
Path and file name of a file to be affected by the function. File path is relative to the set web folder starting with a forward slash /.

### string
Content that will be entered into the file.
- Regular strings such as "Hello, world" should be in quotes.
- SimpleScript code is run without quotes.
- Variables can also be included by adding them to the text.

## Changelog
* Added in version 0.2.

## Examples

### Normal
	s.file_write("/file.txt","Hello world")
