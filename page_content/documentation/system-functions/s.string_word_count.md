## Description
Returns a count of the number of words in the string given.

## Parameters

### string
String of content to check.
  - Regular strings such as "Hello, world" should be in quotes.
  - SimpleScript code is run without quotes.
  - Variables can also be included by adding them to the text.

## Changelog
* Added in version 0.2.

## Examples

### Normal
	v.count=s.string_word_count("how many words am I")
Will return: 5.