# mean-stack-assignment

This assignment includes the following things:

Client side:
Angular js, html, bootstrap [used ngmodules: angular-file-upload]

Server Side:
Node js [used npm modules: Express, multer, line-by-line, iplocation]

The file upload will accept only .log files and send discription to the server along with the file in same request.

Then the file is stored in file system in a specified folder with its original name and extension, duplicate file replaces the existing file

we have an npm module for checking the ip address to which country it belongs to. Based on that we check for the hacked and unhacked lines in the log file and filter them as array of objects and we will send this response in request to the fileupload api hit.

Then this data is displayed in html page with analysis and description as a tooltip.

if we are sending another file, the form will be reset and new output data will be fired.
