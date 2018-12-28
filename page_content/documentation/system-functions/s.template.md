## Description
Template call sets the location of the template file. To see how to use the template system visit the [Template System](/documentation?page=basics%2Ftemplate+system.md) documentation. The template and all text placed in the template will be returned after the script fully runs. If you make any s.echo calls, or other text returns, they will show in the source before the template and template content regardless of where the s.template is set.

## Parameters

### file
Location of the template file (usually .html) relative to the sites www folder.

## Examples

### Set
	s.template("/template.html")
