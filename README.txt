There are 3 folders in this zipped folder
1. certs
whihc contains the certificates we had created for the MQTT server/broker, clients setup.
Also a configuration file which tells what all options where enabled and where the certificates has to be stored in the system.

2. The mqttpub.py and the  mqttsub.py have the python codes to it whhic reads the output of the sensors and then captures the image via the camera and then triggers an email as wells as subscribe the image to a specific topic over the broker.
the subscribers can request for the image by connecting to the specific topic.

3. the Output folder has the screenshots and the images captured as the system was running, also the screenshot of the email that was triggred asd the system found an intruder.