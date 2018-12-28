### Bugs fixed
* None...

### New system functions
* `s.quit()` - Stops any more code execution and shuts SimpleScript down. This is useful for user systems when a user is redirect for not having permission on the page. This will stop the code after it's called from running.
* `s.2fa("sitename")` - Create a new 2FA session for the page, do this before you can call the other 2FA calls or you will just get `FALSE` returned.
* `s.2fa_createsecret()` - Generate a secret code. Store this in your database for the user as you will need it to validate later on.
* `s.2fa_qrcode("sitename","secret")` - Returns a DataURI of a generated QR code using the site name and the secret code you already made. The user scans this OR supply them the secret so they can enter it into the 2FA app they want to use. To use the QR code just place it in a image SRC tag.
* `s.2fa_verifycode("original_secret","2fa_app_code")` - Using the original users secret that you fetch from the user database or other you can compare it to the code a user submits to verify if it's a code generated using the secret.

### Other new features
* None...
