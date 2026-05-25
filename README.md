# trklab_demo - *static*

WEBIODE update - ATC radar track display on web browser.

## How to run HTML page  using local JSON with Chrome?

0) Download this package with the ZIP file. (*This file contains all you need!*)

1) Select a subdirectory where the page and all assets will be deployed. Or create a new directory.

```
	$ mkdir <directory name>
```

2) Extract the archive into the directory just has been created.

```
	$ unzip <zipfilename>.zip
```

3) Create a new subdirectory in the folder just created then copy the full PATH of this new subdirectory *( Ctrl+C ).

```
	$ mkdir private_chrome
```

> After all above you should have a directory structure in your file-system like this below (*files not listed*):

```
../TRKLAB/
	├── css
	├── data
	├── js
	└── private_chrome
```

4) Open a shell window, or commandline window in the directory where the webcontents were placed before. If the current working directory is not the same where the web contents were placed, then simply change it to the webcontents directory:

```	
	$ cd *( Ctrl + V ) or type it manually 
```

5) If you are in the right directory, then start the Chrome in the following way:

```
	chrome or chrome.exe --disable-web-security --user-data-dir=<full path of 'private_chrome' subdirectory>
```

  where the ```<private_chrome>``` is the same which was created in **Step 3**.

6) After a while the new web browser window will appear with some warnings, but we do not take care of the as per now.

7) With ***( Ctrl + O )** open a file browser window and navigate the directory where the '**index.html**' file located. Open it.

8) Play with the map and the colorized track symbols!

Some hints: 
===========
- by pressing left mouse button and move it, the map and all the tracks will be panned around.
- rolling a mousewheel you can zoom in or out the map. (On laptops without mouse use touchpad haptics to access features above.)

Enjoy!



