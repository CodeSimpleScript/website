Function and code to load markdown files from `/docs` ordered by name, generated as one large HTML content page with titles for each item. You will find this WITH and WITHOUT comments

```
f.render_contentmd{
	//Fetch the page we where given by the array_loop so we can load and process it.
	v.file=v.function_passed[0]
	
	//Create a title value from the file name for results like "Version 4"
	v.title=s.file_name(v.file,".md")
	v.title=s.string_word_uppercase(v.title)
	
	//Read the file contents and convert to HTML from Markdown
	v.content=s.file_read(v.file)
	v.content=s.markdown(v.content)
	
	//Send back with the title
	s.echo("<h2>v.title</h2>v.content")
}

//Fetch a list of files in a folder, and use array_loop to send each file to the function
v.array=s.folder_content("/docs")
v.content_processed=s.array_loop("render_contentmd",v.array)

//Show the content we just loaded
s.echo(v.content_processed)
```


```
f.render_contentmd{
	v.file=v.function_passed[0]
	
	v.title=s.file_name(v.file,".md")
	v.title=s.string_word_uppercase(v.title)
	
	v.content=s.file_read(v.file)
	v.content=s.markdown(v.content)
	s.echo("<h2>v.title</h2>v.content")
}

v.array=s.folder_content("/docs")
v.content_processed=s.array_loop("render_contentmd",v.array)
s.echo(v.content_processed)
```