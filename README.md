# Digital_Dramas_Laboratory

If you have problems with the Universal Viewer, follow these instructions or go to: http://ronallo.com/iiif-workshop-new/preparation.html and follow the istructions.
<br>
You will need:
- a local web server (Web Server for Chrome, etc.)
- a network connection

Create a directory called "iif-workshop".
Start your local web server that is serving files from your “iiif-workshop” directory.
<br>
Make sure to check the “Set CORS headers” box.
<br>
<br>
![alt text](https://github.com/ariele-santello/Digital_Dramas_Laboratory/blob/main/assets/img/web-server-for-chrome.png?raw=true)
<br>
Open http://localhost:3000 in a browser
<br>
Download the manifest.json file inside this Github repository and put it in your “iiif-workshop” directory.
<br>
Now you should have a directory with a "manifest.json" file inside.
<br>
Clicking on http://localhost:3000/manifest.json it should open the "manifest.json" file, it means everything is correct.
<br>
Now go at http://ronallo.com/iiif-workshop-new/presentation-api/viewers/universal-viewer.html or at http://universalviewer.io/uv.html?manifest=http://localhost:3000/manifest.json
<br>
You will see the image in Universal Viewer!

