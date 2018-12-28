## Description
Allows you to capture the output of another SimpleScript file after it runs.

## Parameters

### file
Link to the file from your site's web folder. Starts with `/` and can link to files in sub folders `/folder/file.ssc`

## Changelog
* Added in version 0.1.

## Examples

### Run as normal and place output
	s.run("/script.ssc")

### Capture output in a variable
	v.output=s.run("/script.ssc")
	