* `s.math()` - Do math calculations `v.calculated=s.math("(10.2+0.5*(2-0.4))*2+(2.1*4)")`  
* `s.get_ip()` - get visitors true IP address
* `s.file_uri(filepath)` - Will return a base64 encoded version of the file also known as a data URI.  
* `s.system_debug("true")` - Turns on or off the system debug echo in the page source overriding the default set.  
* `s.quit()` - Stops any more code execution and shuts SimpleScript down. This is useful for user systems when a user is redirect for not having permission on the page. This will stop the code after it's called from running.
* `s.2fa("sitename")` - Create a new 2FA session for the page, do this before you can call the other 2FA calls or you will just get `FALSE` returned.
* `s.2fa_createsecret()` - Generate a secret code. Store this in your database for the user as you will need it to validate later on.
* `s.2fa_qrcode("sitename","secret")` - Returns a DataURI of a generated QR code using the site name and the secret code you already made. The user scans this OR supply them the secret so they can enter it into the 2FA app they want to use. To use the QR code just place it in a image SRC tag.
* `s.2fa_verifycode("original_secret","2fa_app_code")` - Using the original users secret that you fetch from the user database or other you can compare it to the code a user submits to verify if it's a code generated using the secret.
* `s.file_uploaded()` - Returns `true` or `false` if the system had a file uploaded to it.
* `s.file_uploaded_name()` - Returns the name of the file uploaded. Remember to clean file names before saving to a database.
* `s.file_uploaded_size()` - Returns the size of the file uploaded in bytes.
* `s.file_uploaded_type()` - Returns the type of the file uploaded for example `image/jpeg`.
* `s.file_uploaded_save("/uploadedimage.jpg")` - Will save the file to disk in your main web folder `default /www`.
* `s.http_request_post(url,array)` - Will make a HTTP POST request to the url given and post the array, if it cant it will post to the page the item `ss_post` with the value of `true`.
* `s.http_request_post_file(url,filepath)` - Will make a HTTP POST request to the url given and post the the file to it. It will be sent as the item name `file`.
* `s.random_string_phrase(number)` - Will generate a random dash separated phrase like `crape-myrtle-pigeon`. The number supplied will be the number of words used. It will default to 50/50 chance of 2 or 3 words.
* `s.string_first_word_uppercase(string)` - Will only make the first word have a upper case starting character, making a string like `crape myrtle pigeon` become `Crape myrtle pigeon`.
* `s.system_maxtime(seconds)` - Sets the max amount of time the page/scripts will run before closing. Default is 20 seconds.
* `s.system_sleep_second(seconds)` - Pauses the script from running for so many seconds.
* `s.system_sleep_ms(millisecond)` - Pauses the script from running for so many milliseconds, so a value of `2000` would be 2 seconds.
* `s.get_useragent()` - Returns the users current useragent string.
* `s.sha1(string)` - returns a sha1 hash of the string given.
* `s.md5(string)` - returns a md5 hash of the string given.
* `s.string_contains(find,string)` - Will return `true` or `false` if the FIND content can be found in the STRING.
* `s.array_keys(array)` - Will return a number array with the values of the keys in the array supplied.
* `s.string_split_array(item,string)` - Will split a string into an array based on a character or string given in the first value.
* `s.array_count(array)` - Returns how many items are in an array.
* `s.convert_timestamp_string_unix(format,timestamp)` - Converts a unix timestamp to a date format. For example the format `D, d M Y` will result in the return of `Sun, 18 Feb 2018`.
* `s.convert_timestamp_string(format,timestamp)` - Converts a timestamp to a date format. For example the format `D, d M Y` will result in the return of `Sun, 18 Feb 2018`.
* `s.covert_unix_timestamp(timestamp)` - Converts a unix timestamp to a SS formatted timestamp.
* `s.string_splitlines_array(string)` - Splits the string given into an array for each line in the string given.
* `s.file_image_resize_square(imagepath,size,[optional]savepath)` - Turns a GIF,PNG,JPEG file into a square down to a size given. It will overwrite the original file if a optional save path is not given.
* `s.file_read_base64(filepath,[optional]haveheader)` - Reads a image or other file into a base64 encoded string with file type set. If as a second option you pass `false` the file type info wont be added before the encoded file.
* `s.check_valid_domain(string)` - Returns `true` if a domain given is a valid root domain like `www.google.ca` and false if not.
* `s.http_request_post_auth(url,array,auth)` - Does a normal POST request with data, but allows you to set a custom auth header like `OAuth sdfm9382fo28p9n2uf89jm982`.
