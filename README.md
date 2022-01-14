# ChatUP-Messenger
This repository is dedicated to a GUI based chat application developed using Java and a simple client server based messaging application developed using C++.
## Aim of the Project
Developing a messaging application using Java features like javafx and scene builder for creating the GUI for the messenger app and demonstrating advanced use of Java. C++ has also been used to develop a simple messaging app based on the console between a single client and single server. The C++ application has been complied on a Ubuntu virtual machine.
## Structure of the Folder
2 main folders
Java Application -> SRC : contains source files 
Java Application -> BUILD : contains the build files
Java Application -> DOC : contains user manuals, documentation and log files that were created during the execution of the application. This includes a Contacts.txt file for storing the names and contacts of the people added by the user. This file is saved locally on the disk every time the application is run serving as backup data. 
Java Application -> RESULTS : contains screenshots of the application when it was under exceution.
Java Application -> image : contains images that were used for testing the application. The Profile pane.
## Structure of the SRC File
The source file contains the following files:
test.cpp, Controller.cpp, chatClient.cpp, chatServer.cpp, chatMultiClient.cpp, chatMultiServer.cpp, chatClient.form, chatServer.form, Home.fxml, Profile.fxml and Contacts.fxml.

### test.cpp -> 
main class in the project. Calls the root file or the main point of start to the application which is the Home.fxml file.
### Conroller.cpp -> 
as the name suggests controls or has the code that checks the functionality of navigation and every widgets present on the panes along with the initialization of the single messaging and chat room messaging feature.
### chatClient.cpp ->
contains code for single client messaging functionality. This code connects to the gui present in the chatClient.form file.
### chatServer.cpp ->
contains code for single server messaging functionality. This code connects to the gui present in the chatServer.form file.
### chatMultiClient.cpp -> 
conatins code for initialising multiple clients.
### chatMultiClient.cpp ->
contains code for connecting with multiple clients or adding multiple clients to the same room.
### Home.fxml ->
contains the xml structure or layout for home page. Makes use of buttons, text fields and labels in javafx.
### Profile.fxml ->
contains the xml structure for profile page. Makes use of buttons, text fields and labels in javafx. Allows user to open a file window using java swing for editing profile image.
### Contacts.fxml ->
contains the xml structure or layout for contacts page. Makes use of buttons, text fields, textfield and labels in javafx.
