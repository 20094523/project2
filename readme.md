## **Purpose**
The project is a combination of an Arduino , a Raspberry Pi and a phone, meant to notify you when a dog bowl has been emptied. 
>This is done by using an LDR and an LED; the LED. when unobstructed by dog food, will shine light onto the LDR, notifying the Arduino -> raspberry pi ->phone that the bowl is empty.

 Instructions for the setup of everything, along with a few images, will be posted below, while the code required to run everything is in the github repository.
## **Setup**
Install the Javascript Arduino Code onto your Arduino (you can adjust the sensitivity of the LDR) using the Arduino IDE found below.
>https://www.arduino.cc/en/software

![plot](https://github.com/20094523/project2/blob/master/images/arduino.png "Arduino Code")


Then you need to set up a Blynk account on your phone and install the Blynk app (found on the app store). After that is done, create a new project, acquire your authorization token, which is needed for your Wyliodrin code to work, and set up a simple notification as shown below.

![plot](https://github.com/20094523/project2/blob/master/images/blynk1.png "blynk1")
![plot](https://github.com/20094523/project2/blob/master/images/blynk2.png "blynk2")
![plot](https://github.com/20094523/project2/blob/master/images/blynk5.png "blynk3")
![plot](https://github.com/20094523/project2/blob/master/images/blynkemail.png "email")
![plot](https://github.com/20094523/project2/blob/master/images/blynk3.png "blynk4")
![plot](https://github.com/20094523/project2/blob/master/images/blynk4.png "blynk5")

Then write and run the python code onto your Raspberry Pi, using Wyliodrin Studio found below again. Make sure to install Blynk on your raspberry pi so that it can connect to your phone! (as with before, you can adjust the time between notifications inside of the code)
>   https://wyliodrin.studio/

![plot](https://github.com/20094523/project2/blob/master/images/wyliodrin.png "blynk5")

Set up your breadboard, arduino and raspberry pi as shown in the images below.

![plot](https://github.com/20094523/project2/blob/master/images/breadboard2.png "Real Life Example")
![plot](https://github.com/20094523/project2/blob/master/images/breadboard1.png "Diagram")

After all of this has been set up, your app will notify you when the LDR is unobstructed (food bowl is empty).

![plot](https://github.com/20094523/project2/blob/master/images/final.png "Notification Working")
