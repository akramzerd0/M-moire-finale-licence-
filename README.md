# licence memoire finale-
-- analysis and improvement of the Needham schreoder security protocol (based on symmetric cryptography)

  * these files can only be excuted using the scyther tool and here is the website where it can be downloaded =>https://people.cispa.io/cas.cremers/scyther/
     
* when we download the file, 3 more  components are also needed so scyther tool can function properly :        
  
1) The GraphViz library  ( the website =>http://www.graphviz.org/)  
   
2) Python but Scyther does not support Python 3 so any python 2.X version will do the work.  (website =>http://www.python.org/download/) 

3) and finally wxPython libraries (website =>http://www.wxpython.org/download.php) 
when all of the above components are downloaded , we open the compressed scyther folder and extract it where we want and then scroll down to the file called "scyther-gui.py" , we click on it , a window that has a white area appears where code can be written ,
we click on "file" from the top bar and then "open", a box will appear with all he files , we select the spdl code file from the github repository that we want to run after downloading it then we click okey ,
the protocol code appears and we click verify to check for fails and oks.
