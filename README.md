#  Install SlideController

Install [SlideController](apk/SlideController.apk) app on you're phone

# Install RPCServer

RPCServer is a server that SlideController app uses to connect to you're computer.

The following are steps to help you install RPCServer in you're computer:

## step 1: 

Download [RPCServer](RCPServer/RPCServer.jar) 

## step 2:

Create a new file and copy/paste this line 

```bash
java --module-path  JAVAFX_Path --add-modules=javafx.controls,javafx.fxml -jar .\RPCServer_jar\RPCServer.jar
```
Please be sure to replace JAVAFX_Path with the real path or javafx in you're pc, if you don't have javafx installed, check this [link](https://gluonhq.com/products/javafx/) 

## step 3:

Save the file as .bat example: server.bat

## step 4:

Finally, you can double-click on the .bat file so the server will be launch.