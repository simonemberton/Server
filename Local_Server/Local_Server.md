### Set up local server

Up until now we've been opening our HTML files in a web browser to view it. However, when loading external data sources (such as image and video files), it is necessary to run a local web server.

There are a range of options to choose from. A good resource for a variety of options can be found [HERE](https://github.com/processing/p5.js/wiki/Local-server).

On your own machines you could use a server like [MAMP](http://mamp.info/en/) for Macs and [XAMPP](https://www.apachefriends.org/index.html) for PCs.

To create a local server on university machines you can follow the following instructions to use a http server with Python.  

Open the terminal window (you can find it in Applications/Utilities) and navigate to the folder you want the server in (e.g. the one that contains your `sketch.js` file).  Type `cd` to change the current directory followed by a space followed by the location of the folder (you can drag the folder into the terminal window to get this location).  Then type `python3 -m http.server 8000` to open a http server on port 8000.  Now open your browser and go to http://localhost:8000/index.html.  If you need to stop the server you can type `Ctrl + c`.
