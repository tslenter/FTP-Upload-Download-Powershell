# FTP-Upload-Download-Powershell
Script for upload and download with powershell

A simple powershell script for listing, downloading and uploading files from/to a ftp server.

Change the variables and you are good to go:

```
....

#FTP Server Information - SET VARIABLES
$ftp = "ftp://remoteaccess.xxx.local/"  <<<--- FTP Server
$user = 'user'  <<<--- username
$pass = 'password' <<<--- password
$folder = '/' <<<--- Path within the FTP root
$target = "d:\ftp\" <<<--- Computer destination / target directory

....
```

After the variable change copy the code op STEP 1 to the powershell console. 
The next step is to run a code block from STEP 2. Choose between the UPLOAD or DOWNLOAD code block.
