# Home_automation_using_google_assistant
This is a Google assistant based home automation project. In this the home appliances are connected to a remote switch called relay module.
The relay module helps in connecting the circuit to a new device, connected in the same circuit, without disconnecting the power supply.
The circuit diagram is given on this link- https://drive.google.com/file/d/1zG19PlVLJv5A_ymdABVbf3hZJrPf_ma3/view?usp=sharing
To get started with the project you have to do these following steps:
  >Goto https://io.adafruit.com and click on Get Started with Free.
  >Fill up all the details into it and create a new account.
  >Now open a new tab and reopen the adafruit site. There you have to login to your account and Create a new Dashboard. Name it and write some about it and create it.
  >After creating it, on the top right side click on (+) symbol to add gui buttons to see the effect. You should select toggle icon to create it.
  >A drop down box will appear, name it as Relay1, Relay2 and so on as no. of relays you have used in the project (this project is based on 4 relay setup).
  >After this select first relay in the check box and click on next step. There chanage the On button to '1' and Off button to '0'. And create it.
  >Do this for all the relays by going to (+) and selecting the relay check box.
  >Then click on setting icon near to (+) symbol. And rearrange the order of the relays and save it.
  >After this click on the key symbol on the right side of the (+) symbol and get the user name name and pass key.
  >Write that user name and pass key in the code where AOI_USERNAME and AOI_KEY is defined. Also edit the wifi user name and password of your wifi.
  >Now upload the code to the nodemcu esp8266.
  >Now goto https://ifttt.com and signin with same mail id which you have entered in the adafruit site.
  >After signing in goto my applets and click on New Applet. Then a statement will appear as "if this then that" click on "this".
  >Then in the search bar search for Google assistant and select connect. Allow all the permission and select the "Say a simple phrase".
  >Then fill the box according to your needs and click on Create Trigger. Then select the "that" button and search for Adafruit and click on connect.
  >After this authorize the app and select "send data to adafruit io". Then in Feed name select Relay name and "1" or "0" for data to save for which you are doing this. And create action.
  >Repeat all the step from New Applet creation upto this for every relay. There will be 2 applet for each relay (one for switch on and other for switch off).
  >After successfully creating all the switch action, then power up the nodemcu and goto adafruit site where you created toggling switch.
  >Switch On and Off the buttons and see for the On Off toggling of LED on the relay board. After this connect an android phone with the same wifi network and command the same line you have enetred in the ifttt applets.
  >Do not connect the high power devices before testing the code for successfull working.


This is all for the Google Assistant based Home Automation.
