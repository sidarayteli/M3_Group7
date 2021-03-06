# About BiCom System

## 1.1 Abstract
Over 70% of the vehicle made today come with a Bi-Com system which
is the extinction of the unidirectional RKE to bidirectional RKE (Remote
Keyless Entry) system either standard or as an option.

## 1.2 Description
Bi-Com System is Bidirectional RKE system which consists of
transmitter (Key-fob) and receiver (Car) include some functions. By using these
functions, we can check the car status information. The most used frequency for
transmitting and receiving is 315MHz in the U.S and Japan, and 433.92MHz in
Europe. Most used Bi-Com system alarm the vehicle against theft and lock and
unlock the door and trunk. Some include remote start and car finder function.
The most Bi-Com system design are achieving Low power consumption in both
Transmitter and Receiver, while achieving good range and reliability for the Bi-
Com system.
Bi-Com system allows a user to lock, unlock the care and to check the
windows status, alarm status, Battery status information etc.… This application
note describes how Bi-Com system Work and ways to meet the primary design
challenges, which are low power consumption, Bi-Com Transmitter, Receiver
range and reliability.


## 1.3 Features
 * It shall display window satus of car for one User Button Click
 * It shall display alarm satus of car Two User Button Clicks
 * It shall display battery information of car for Three User Button Clicks
 * It shall display door satus of car for Four User Button Clicks




## 1.4 SWOT Analysis 
![SWOT_Bicom](https://user-images.githubusercontent.com/46900710/157823346-22f82eb1-e2c2-4ecb-a66d-7708bdf6b353.png)


## 1.5 5W 1H
![5W_1H](https://user-images.githubusercontent.com/46900710/157823406-81a07e0c-4a83-4760-ba16-98c8667c78e4.png)


## Requirements

## 2.1 Highlevel requirements
|ID|Description|
|---|----------|
|HLR_1|Windows status (Open or closed) shall be displayed by using the Key-fob (Transmitter)|
|HLR_2|Alarm status shall be displayed (Activate or deactivate)|
|HLR_3|Car battery status information shall be displayed (Weather the Battery is Full or not)|
|HLR_4|Door status shall be displayed (Lock or Unlock)|
|HLR_5|System shall be bidirectional RKE (Bi-Com)|

## 2.2 Lowlevel requirements
|ID|Description|
|---|----------|
|LLR_1|When button is pressed one’s, all led shall turn ON at same time|
|LLR_2|When button is pressed twice, all led shall turn OFF at same time|
|LLR_3|When button is pressed three times, all led shall turn ON in clockwise direction|
|LLR_4|When button is pressed four times, all led shall turn ON in anti-clockwise direction|
