# Initial-Router-Configuration
The topology for this project is show below:

![topology](https://user-images.githubusercontent.com/69259617/117096015-ec0bcb80-ad35-11eb-9f90-6bcc11163c6b.JPG)

In this project, a 1941 router has been configured. Simple configurations such as assigning hostname and line console passwords, Privileged EXEC mode passwords and giving message of the day have been configured. 

With the help of the **service password-encryption** command, all the passwords have been encrypted and therefore none of the passwords can be seen in plain text on given the command **show running-config**. 

The output of the encrypted passwords, message of the day and assigned hostname is shown below:

![rc_Pass](https://user-images.githubusercontent.com/69259617/117096081-02b22280-ad36-11eb-9668-af54c5bb2eb3.JPG)

Configuring password for the Privileged EXEC mode and the line console is the same as that of a Switch. 
Finally, saving all the configuratoins too the startup config file by issuing the command **copy running-config startup-config**
