Fetch stored data from one file to other.

Description-  In this there is a JS file named as Filesystem.js which is used to ferch the stored data from other html file 
named as calculator.html. In order to fetch the data, fs module is loaded using the require() function. In the require 
function , fs parameter is passed . HTTP module is used which allows to transfer data over http.HTTP module can create an 
http server that listen to server ports and give a response back to the client.
Syntax for creating http server is -:
http.createServer().listen(8080);
After that file is read using the fs.readFile() . The file that you want to read is passed as parameter to this function.If the 
user wants to send the file in html format then resp.writeHead(status , content -type) is given.After that the data is sent 
using the res.write()
