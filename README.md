# AIFCOMSS

Requires the prior installation of:

 1) node.js ( https://nodejs.org/en/ ) <br>
 2) Cesium ( http://cesiumjs.org/downloads.html ) <br>
 3) the <a href="https://www.npmjs.com/package/serialport">node serialport</a> library (which you should install from the npm registry by just typing "npm install serialport" on a command line) <br>
 4) the <a href="https://www.npmjs.com/package/ws">node ws</a> websocket library (which you should install from the npm registry by just typing "npm install ws" on a command line) <br>
 5) p5.js ( https://p5js.org/download/ ).  Include the p5.js files in a subdirectory of the Cesium main directory above. <br>

Install each one of the above five, then:

 a) Download this (AIFCOMSS) repository to your Cesium main directory (which should replace the default server.js file that Cesium has included), <br>
 b) In that same Cesium main directory, type  "node server.js | tee \<yourlogfile.log\>" , <br>
 c) Then, in a web browser, go to:  http://localhost:8080/AIFCOMSS.html . <br>

You should, then, have AIFCOMSS running in your web browser.

Please ask me any questions that come up (jalbert@uvic.ca).
