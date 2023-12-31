### This is the backend of Trim PDF project. Here is the link of frontend - https://github.com/piyushdahiya1218/Trim_PDF/tree/master/frontend

When the backend gets a request to convert the original PDF for the very first time, it downloads **IronPDF Engine** which is a part of IronPDF library. It can take upto **1 minute** to download and extract this Engine depending upon the internet connection. Once this Engine setup is done, all the subsequest requests to convert the PDF take only upto 5 seconds!

Steps to setup the backend - 
2. Clone this project and open it in VS Code.
3. Open terminal (make sure to `cd` into backend) and run command `npm install`.
4. After node_modules are installed, run `npm start` to start the server on localhost port **5000** by default. If you already have something else running on this port then either kill that process or change the port by going into the file *www* inside *bin* folder and change the port number.
5. After server is started successfully, open this address `localhost:5000` in browser (change port number if running on some other port) to make sure the server is running.

Please keep the terminal open in VS Code after starting the server to view download and extraction progress of **IronPDF Engine**.

#### NOTE: If the Iron PDF Engine gives an error similar to `Error: Cannot connect to IronPdfEngine: Error14 UNAVAILABLE: No connection established. Last error: connect ECONNREFUSED`, then please try running the project on Windows machine or MacOS with intel chip. This error is caused by node server and not the project itself.
