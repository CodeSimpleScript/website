## Description
Will add content to the end of the file given. This is part of the file system functions.  Improper use of the file system functions will result in loss of data.

## Parameters

### file
Path and file name of a file to be affected by the function. File path is relative to the set web folder starting with a forward slash /.

### string
Content that will be entered into the end file.
- Regular strings such as "Hello, world" should be in quotes.
- SimpleScript code is run without quotes.
- Variables can also be included by adding them to the text.

## Return
Will return TRUE or FALSE after run.

## Examples

```
s.file_add("/file.txt","Just a new bit of info")
```
