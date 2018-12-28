### Bugs fixed
* None...

### New system functions
* `s.file_uploaded()` - Returns `true` or `false` if the system had a file uploaded to it.
* `s.file_uploaded_name()` - Returns the name of the file uploaded. Remember to clean file names before saving to a database.
* `s.file_uploaded_size()` - Returns the size of the file uploaded in bytes.
* `s.file_uploaded_type()` - Returns the type of the file uploaded for example `image/jpeg`.
* `s.file_uploaded_save("/uploadedimage.jpg")` - Will save the file to disk in your main web folder `default /www`.
* `s.http_request_post(url,array)` - Will make a HTTP POST request to the url given and post the array, if it cant it will post to the page the item `ss_post` with the value of `true`.
* `s.http_request_post_file(url,filepath)` - Will make a HTTP POST request to the url given and post the the file to it. It will be sent as the item name `file`.

### Other new features
* Fixed and new clean error pages.
