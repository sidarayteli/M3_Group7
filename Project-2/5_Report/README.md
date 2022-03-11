## Abstract
Over 70% of the vehicle made today come with a Bi-Com system which
is the extinction of the unidirectional RKE to bidirectional RKE (Remote
Keyless Entry) system either standard or as an option.


## Description
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


## Features
 * It shall display window satus of car for one User Button Click
 * It shall display alarm satus of car Two User Button Clicks
 * It shall display battery information of car for Three User Button Clicks
 * It shall display door satus of car for Four User Button Clicks


## Requirements

## Highlevel requirements
|ID|Description|
|---|----------|
|HLR_1|Windows status (Open or closed) shall be displayed by using the Key-fob (Transmitter)|
|HLR_2|Alarm status shall be displayed (Activate or deactivate)|
|HLR_3|Car battery status information shall be displayed (Weather the Battery is Full or not)|
|HLR_4|Door status shall be displayed (Open or closed)|
|HLR_5|System shall be bidirectional RKE (Bi-Com)|

## Lowlevel requirements
|ID|Description|
|---|----------|
|LLR_1|When button is pressed one’s, all led shall turn ON at same time|
|LLR_2|When button is pressed twice, all led shall turn OFF at same time|
|LLR_3|When button is pressed three times, all led shall turn ON in clockwise direction|
|LLR_4|When button is pressed four times, all led shall turn ON in anti-clockwise direction|

## SWOT Analysis 
![image](https://user-images.githubusercontent.com/46954351/157818376-077e6acb-bbcc-47ae-bf26-9a552518a048.png)


## 5W's and 1H
![image](https://user-images.githubusercontent.com/46954351/157818604-ac37547f-cf55-4cd3-9f25-69cd211b752e.png)

## Testplan and Output

## Highlevel Testplan

|TEST ID|DESCRIPTION|Input|Expected Output|Actual Output|Status|
|-------|-----------|------|---------------|------------|------|
|HLT_1|Windows status shall be displayed using Key-fob (Wireless device)|User button press|Window status (Open or Close)|Window status (Open or Close)|
|HLT_2|Alarm Status shall be displayed|User button press|Alarm status|Alarm status|
|HLT_3|Car Battery status information|User button press|Battery status (Full or not)|Battery status (Full or not)|
|HLT_4|Door status displayed|User button press|Door status (open or close)|Door status (open or close)|


## Lowlevel Testplan
|TEST ID|DESCRIPTION|Input|Expected Output|Actual Output|Status|
|-------|-----------|------|---------------|------------|------|
|LLT_1|Window Status|User button press one’s|All LED turn ON|All LED turn ON|
|LLT_2|Alarm Status|User button press Twice|All LED’s turn OFF.|All LED’s turn OFF|
|LLT_3|Car battery status|User button press 3-times|All LED’s Turn ON clockwise.|All LED’s Turn ON clockwise|
|LLT_4|Door Status|User button press 4-times|All LED’s turn ON anti-clockwise.|All LED’s turn ON anti-clockwise|


## Usecase Diagram

![USECASE Diagram](https://user-images.githubusercontent.com/98537406/157823660-0f04a48c-e453-4e59-b09d-78f30a3b84ea.png)

## Flowchart
![image](https://user-images.githubusercontent.com/46954351/157822868-66c2d48f-1f7f-41a1-ad91-42a663e71630.png)

## lowlevel requirement flowchart
![image](https://user-images.githubusercontent.com/46954351/157823212-556a7626-5785-4e41-8360-c281bedb4c24.png)











