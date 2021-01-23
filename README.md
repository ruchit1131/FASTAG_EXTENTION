# FASTAG_EXTENTION

## GETTING STARTED

(The user must have python installed on the system)

+  Download the WinRar Archive file.
+  Unzip the file.
+  Open FASTAG-1.0
+  Hold Shift Key and right click.
+  Click on ‘Open Powershell Window here’.
+  Type : python setup.py install
+  Type: cd bin
+  Type: python Run.py


## WORKING

The customer can add money in his account using various banking options. He can also view his
Balance. The customer will get a sms on the registered phone number informing him about his
balance.
The police can scan the FasTag and collect the challan, by choosing which rule was violated; in the
app. The vehicle type of the violator is an attribute of its account. When the police scans the FasTag, 
the app automatically opens the rule violation list for the particular type of vehicle without manual
entry.
The petrol pump executive will scan the FasTag and enter the amount fuel to be filled. The
customer will get a verification OTP and after verifying the OTP, the amount will be deducted from
the customers FasTag account. 

# MODULES

FASTAG : This module contains two scripts namely getotp and clearscr.
The getotp script contains a function which generates a random 5 digit OTP used for the
confirmation of Petrol Pump payments making them secure.
The clearscr script contains a function which is used to clear the command prompt(for Windows)

# API

fast2sms : This API is used to send text messages to the phone number of the registered user.
The Developer’s API has a unique API Authorization Key which is used to send 20 free sms per day. 


