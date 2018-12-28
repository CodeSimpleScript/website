## Description
Allows you to trim a string to a max number of characters.

## Parameters

### string
String of content that will be trimed.
  - Regular strings such as "Hello, world" should be in quotes.
  - SimpleScript code is run without quotes.
  - Variables can also be included by adding them to the text.

### number
Max size in characters that the string can be.

## Changelog
* Added in version 0.2.

## Examples

### Normal
	v.string=s.string_trim("Did you know that cats are awesome.",26)
Will return "Did you know that cats are".