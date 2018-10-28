# Health-monitoring-System-
Health monitoring system is a remotely accessible and monitorable device for patient health care . 
i.	Circuit Formation:
a.	Initially we accumulate all the items needed as mentioned in the requirements.
b.	Now make the connections for circuit as per the circuit diagram.
ii. Cloud Creation
a.	Now we need to make a link over the cloud and here we are using ThinkSpeakcloud for this purpose.
b.	Now make a account on ThinkSpeak (its free) and sign in over the account.
c.	Now you will be seeing some tabs where you select channel tab.
d.	Under the Channel tab you could be able to see the new channel button click over it . 
e.	Now make a new channel and specify the name and other details as per your choice. 
f.	Now after going on to the channel you would see some tabs. Choose the API KEYS tab 	and copy or note the API KEY somewhere down.
 
g.	Now you need to use this API KEY in the code.
ii.	Setting up Arduino and Coding 
a.	First you need to download ARDUINO IDE in your pc .
b.	Now open Arduino IDE and go to file and then preferences. Now add this link over the Additional Board Manager URLS:
a.	http://arduino.esp8266.com/stable/package_esp8266com_index.json .
 
c.	Now go to Tools and under that to Boards-> Board Manager.
d.	Now type esp8266 in search box and install the second module with the latest version.
 
e.	Now you are ready with the coding part.
f.	Use the code which is been provided in the document.
g.	In the Api key add api of the channel you made on Thinkspeak.
h.	Add your wifi name and password over ssid and password respectively.
i.	Now click on compile and then upload and the node mcu will start blinking indicating that the data is getting uploaded. 
j.	Once its done open the serial Monitor and check whether you are getting the connection status true ..
iv.	Now switch over to ThinkSpeak and check whether data is been received you could see the data graph under the private view. You could also send the data as a XML file or CSV file for further analysis.
v.	Here we are done with the project. Congrats you did it . 
