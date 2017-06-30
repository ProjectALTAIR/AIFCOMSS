# AIFCOMSS

First, make sure that your Mac, Linux, or Windows computer has Python ( https://www.python.org -- version 2.7 is best ) installed (and if not, then please install it, using the instructions on the https://www.python.org website). <br>

Then additionally, for the specific case of Windows machines (but this is not necessary on Mac or Linux), please also first install Visual Studio ( https://www.visualstudio.com , or make sure Visual Studio is already installed on your Windows machine). Note that on Windows machines, after installing Visual Studio, all commands below must be run in powershell, rather than in the standard Windows command -- you can access powershell from the standard Windows command by typing: $ powershell<br>

Following that, on <i>any</i> platform (Mac, Linux, or Windows), we require the installation of: <br>

 1) Node.js ( https://nodejs.org/en/ ) <br>
 2) Cesium ( http://cesiumjs.org/downloads.html ) <br>

Install both of the above on your computer, then: <br>

 a) Download this (AIFCOMSS) repository to your Cesium main directory (which should replace the default server.js file that Cesium has included) ; <br>
 b) In that same Cesium main directory, type  "npm update" , this will install all the necessary node packages, including serialport and ws ; <br>
 c) In that same Cesium main directory, type  "node server.js | tee <i>yourlogfile.log</i>" ; <br>
 d) Then, in a web browser, go to:  http://localhost:8080/AIFCOMSS.html . <br>

You should, then, have AIFCOMSS running in your web browser. <br>

Please ask me any questions that come up (jalbert@uvic.ca).
