# **Wiper Control System**

## **About Wiper Control System**

## **Abstract**

Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen. The previous system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. Thus, this system is proposed to solve these problems. The objectives of this project are to upgrade the older cars system by providing wiping system, to improve the system by using actuator and pull switch(using same switch for multi purpose by stepwise switching) and controlling the engine and speed of the wipers with the single switch.

## **Description**

Wiper Control System is an Electronic device which is a alternative from the normal wiper tool in the cars in this system we will use the single switch to control the Ignition button(On the Motor) on ACC position As a first press and on the wiper system by pressing the button second time and Changing the speed of the wipers on the third press of the button and by pressing the button fourth time the motor will be OFF on the lock position. And all this process was done by using LED's in simulation Tool.

## **Features**

  - ON The Motor(Ignition Position)
  - OFF the Motor
  - Power ON Wipers
  - Speed Controll of wipers

## **swot analysis**

![swotanalisys](https://user-images.githubusercontent.com/101035658/168055063-47ab88cc-ac8f-4dbf-9985-a2b097a59848.jpeg)

## **5W & 1H**

![5W1H Method](https://user-images.githubusercontent.com/101035658/168057015-4589d9cb-0065-45a6-b55e-0f3a93a768db.png)

## *High level Requirements*

<html>
<body>
<!--StartFragment-->

ID | Description
-- | --
HLR-1 | User shall be able to ON the motor
HLR-2 | User shall be able to ON the wipers and controll the speed of wipers 
HLR-3 | User shall be able to OFF the wiper
HLR-4 | User shall be able to OFF the motor

<!--EndFragment-->
</body>
</html>

## *Low level Requirements*

<html>
<body>
<!--StartFragment-->

ID | Description
-- | --
LLR-1 | When user presses the switch for first time for two seconds, The Red LED is ON
LLR-2 | When user presses the button twice,  Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz
LLR-3 | When user presses the button  fourth time The LED glow pattern stops 
LLR-4 | Again pressing the button for two seconds The Red LED is OFF

<!--EndFragment-->
</body>
</html>

# **Behavioural Diagrams**

## High Level Flow Chart Behavioural Diagram

![1jpg](https://user-images.githubusercontent.com/101035658/168073380-9a1d371b-652d-4c0b-95d1-38a2409ddc3d.jpeg)


## Low Level Diagrames

![2jpg](https://user-images.githubusercontent.com/101035658/168073454-579abafc-cd4b-49d6-aaff-b8b1665c77f4.jpeg)

# HIGH LEVEL TEST PLAN 
 
<html> 
<body> 
<!--StartFragment--> 
 
Test ID | Description | Input | Expected output | Actual Output | status 
-- | -- | -- | -- | -- | -- 
01 | Ignition On |  Pressing Button 1st 2sec  | key status | Key Status Displayed |✅ 
02 | Wiper On | Pressing user button once | Wiper Status-1Hz | Wiper Status Displayed |✅ 
03 | Wiper On | Pressing user button twice | Wiper Status-4Hz | Wiper Status Displayed |✅ 
04 | Wiper On | Pressing user button thrice | Wiper Status-8Hz | Wiper Status Displayed |✅ 
05 | Ignition Off | Pressing Button 1st 2sec  | Ignition key status | key status Displayed |✅ 
 
<!--EndFragment--> 
</body> 
</html> 
 
 
# LOW LEVEL TEST PLAN 
 
<html> 
<body> 
<!--StartFragment--> 
 
Description | Input | Expected output | Actual Output | Status 
-- | -- | -- | -- | --  
ignition_on() | User Button Press 1st 2sec | RED LED ON | RED LED ON | ✅ 
LED cycle | Button Press once | All LEDs ON | All LEDs ON | ✅ 
LED cycle | Button Press twice | All LEDs ON | All LEDs ON | ✅ 
LED cycle | Button Press thrice | All LEDs ON | All LEDs ON | ✅ 
ignition_off() | User Button Press 2nd 2sec | RED LED OFF | RED LED OFF | ✅ 
 
<!--EndFragment--> 
</body> 
</html>

# **OUTPUT**
![photo_2022-05-14_10-35-29](https://user-images.githubusercontent.com/101035658/168411780-85ceb31f-dbbc-4c14-ae01-5dbc8445adcb.jpg)

![1 3](https://user-images.githubusercontent.com/101035658/168411717-9fbd2982-7714-4823-b76f-bcbfead5c014.jpg)

![1 6](https://user-images.githubusercontent.com/101035658/168411757-99b6207d-f961-4ea3-aeeb-11d38c6190f4.jpg)

![1 4](https://user-images.githubusercontent.com/101035658/168411715-de195ad6-be5c-4b78-a796-84a4938f9c92.jpg)

![1 2](https://user-images.githubusercontent.com/101035658/168411718-58d5b9da-4e82-444d-a0ed-2113f8d969ed.jpg)

