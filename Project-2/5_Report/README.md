# BiCom System
---
## TABLE OF CONTENTS
---
1_Description

* [1.1 Abstract](#11-abstract)
* [1.2 Description](#12-description)
* [1.3 Features](#13-features)
* [1.4 SWOT Analysis](#14-swot-analysis)
* [1.5 5W 1H](#15-5w-1h)


2_Requirements

* [2.1 Highlevel requirements](#21-highlevel-requirements)
* [2.2 Lowlevel requirements](#22-lowlevel-requirements)



3. Architectures

 * [3.1 Usecase Diagram](#31-usecase-diagram)
 * [3.2 Flow-Chart](#32-flowchart)
 * [3.3 Low level requirements flow-chart](#33-lowlevel-requirement-flowchart)
 * [3.4 Low level Diagram](#34-low-level-diagram)



4. Test plans

 * [4.1 High level test plan](#41-highlevel-testplan)
 * [4.2 Low level test plan](#42-lowlevel-testplan)
 
5. References

---



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

---
## 2 Requirements

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


---
## 3 Architecture

## 3.1 Usecase Diagram

![USECASE Diagram](https://user-images.githubusercontent.com/98537406/157825453-14ea90bf-eecf-4857-98bd-257a2d0466ee.png)

## 3.2 Flowchart
![image](https://user-images.githubusercontent.com/46954351/157822868-66c2d48f-1f7f-41a1-ad91-42a663e71630.png)

## 3.3 lowlevel requirement flowchart
![image](https://user-images.githubusercontent.com/46954351/157823212-556a7626-5785-4e41-8360-c281bedb4c24.png)


## 3.4 Low level Diagram

![Lowlevel-Diagram](https://user-images.githubusercontent.com/98537406/157835193-eaf89f92-04ed-4a9b-acf7-a699c50a205e.png)

---

## 4 Testplan and Output

## 4.1 Highlevel Testplan

|TEST ID|DESCRIPTION|Input|Expected Output|Actual Output|Status|
|-------|-----------|------|---------------|------------|------|
|HLT_1|Windows status shall be displayed using Key-fob (Wireless device)|User button press|Window status (Open or Close)|Window status (Open or Close)|
|HLT_2|Alarm Status shall be displayed|User button press|Alarm status|Alarm status|
|HLT_3|Car Battery status information|User button press|Battery status (Full or not)|Battery status (Full or not)|
|HLT_4|Door status displayed|User button press|Door status (open or close)|Door status (Lock or Unlock)|


## 4.2 Lowlevel Testplan
|TEST ID|DESCRIPTION|Input|Expected Output|Actual Output|Status|
|-------|-----------|------|---------------|------------|------|
|LLT_1|Window Status|User button press one’s|All LED turn ON|All LED turn ON|
|LLT_2|Alarm Status|User button press Twice|All LED’s turn OFF.|All LED’s turn OFF|
|LLT_3|Car battery status|User button press 3-times|All LED’s Turn ON clockwise.|All LED’s Turn ON clockwise|
|LLT_4|Door Status|User button press 4-times|All LED’s turn ON anti-clockwise.|All LED’s turn ON anti-clockwise|


---

## 5 References
##  5.1 One Car, Two Frames: Attacks on Hitag-2 Remote Keyless Entry Systems Revisited
### * https://www.usenix.org/system/files/conference/woot17/woot17-paper-benadjila.pdf





