#README

-This Web Application(written using the Model-View-Controller principle) allows the user to run anomaly detections from one of two chosen algorithms: regression or hybrid  (written in c++).
  we have also included two csv files: the first one containing regular data (trainFile.csv) and the second one (testFile.csv file) to test for and find any anomalies. 
  The Application will then display the results on the webpage localhost:8080(our index.html file).

 In order to run it you should download 'node.js'(we used express frame work and npm library) first.
 then open the terminal window on your computer from the 'controller' directory of the web and then type the following commands:
1. npm init --yes
2. npm i express
3. npm i express-fileupload
4. node server.js
5. open 'localhost:8080'
you can then upload any two csv files and begin looking for anomalies 


