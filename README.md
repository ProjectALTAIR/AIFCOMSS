# AIFCOMSS

Requires the prior installation of: <br>

 1) node.js ( https://nodejs.org/en/ ) <br>
 2) Cesium ( http://cesiumjs.org/downloads.html ) <br>

Install both of the above on your computer, then: <br>

 a) Download this (AIFCOMSS) repository to your Cesium main directory (which should replace the default server.js file that Cesium has included) ; <br>
 b) In that same Cesium main directory, type  "npm update" , this will install all the necessary node packages, including serialport and ws ; <br>
 b) In that same Cesium main directory, type  "node server.js | tee <i>yourlogfile.log</i>" ; <br>
 c) Then, in a web browser, go to:  http://localhost:8080/AIFCOMSS.html . <br>

You should, then, have AIFCOMSS running in your web browser. <br>

Please ask me any questions that come up (jalbert@uvic.ca).
