## **Purpose**
The project is a combination of an Arduino , a Raspberry Pi and a phone, meant to notify you when a dog bowl has been emptied. Instructions for the setup of everything, ## **Purpose**
The project is a combination of an Arduino , a Raspberry Pi and a phone, meant to notify you when a dog bowl has been emptied. 
>This is done by using an LDR and an LED; the LED. when unobstructed by dog food, will shine light onto the LDR, notifying the Arduino -> raspberry pi ->phone that the bowl is empty.

 Instructions for the setup of everything, along with a few images, will be posted below, while the code required to run everything is in the github repository.
## **Setup**
Install the Javascript Arduino Code onto your Arduino (you can adjust the sensitivity of the LDR) using the Arduino IDE found below.
>https://www.arduino.cc/en/software

insert images here


Then you need to set up a Blynk account on your phone and install the Blynk app (found on the app store). After that is done, create a new project, acquire your authorization token, which is needed for your Wyliodrin code to work.

insert images here

Then write and run the python code onto your Raspberry Pi, using Wyliodrin Studio found below again. (as with before, you can adjust the time between notifications inside of the code)
>   https://wyliodrin.studio/

insert images here


Set up your breadboard as shown below. Diagram 
