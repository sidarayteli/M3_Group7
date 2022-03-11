#  About Remote KeyLess Entry(RKE)
1_Description

* [1.1 Abstract](#11-abstract)
* [1.2 Objectives](#12-objectives)
* [1.3 SWOT Analysis](#13-swot-analysis)
* [1.4 5W 1H](#14-5w-1h)
---
2_Requirements

* [2.1 Highlevel requirements](#21-highlevel-requirements)
* [2.2 Lowlevel requirements](#22-lowlevel-requirements)

---
3.  Design and Architectures

 * [3.1 Usecase Diagram](#31-usecase-diagram)
 * [3.2 Behavioural Diagrams](#32-behavioural-diagrams)
 * [3.2.1 High Level Requirement Flowchart](#321-high-level-requirement-flowchart)
 * [3.2.2 Low Level Requirement Flowchart](#322-low-level-requirement-flowchart)
 ---
4. Test plans

 * [4.1 Highlevel testplan](#41-highlevel-testplan)
 * [4.2 Lowlevel testplan](#42-lowlevel-testplan)

---





## 1.1 Abstract
* Remote keyless entry (RKE) is an electronic access system that can be controlled from a distance. RKEs, which are typically used to remotely lock or unlock doors, require the end user to initiate an action that will cause a physical or software key fob to transmit a radio signal to a receiver that controls an electronic lock. Typically, the action is to press a button on a physical fob.
* A remote keyless entry car kit doesn’t rely on a physical button or panel in order to get into your vehicle, but instead it has a sensor that detects your remote keyless key fob within a certain range of your vehicle. It then unlocks once you touch the door handle, but only while the key is nearby. Remote keyless entry cars also often allow for remote starting, as long as the remote key fob is within a short distance of the vehicle. Remote keyless communications are done through encrypted radio signals, and this can either be done through short range radio to a remote key fob in your pocket, or it can be hooked up to a smartphone system and can actually be controlled over cellular networks from anywhere in the world.



## 1.2 Objectives
* It shall Lock the car once user click the remote button one time, Along with that all led on at the same time
* It shall Unlock the car once user click the remote button two times, Along with that all led off at the same time
* It can activate/deactivate the alarm once the user clicks remote button three times, Along with that all led on in clockwise manner
* It shall activate approach light for Four User Button Clicks Whenever user press remote button four times that time all led on in anti-clockwise manner

## 1.3 SWOT Analysis
![image](https://user-images.githubusercontent.com/46954351/157859918-b541e40f-b350-4776-9f7b-7c13800b71da.png)



 ## 1.4 5W 1H
![5w1h](https://user-images.githubusercontent.com/46900710/157737280-2c2ee9a5-a800-40fc-b3e6-fa47862f5b7b.JPG)


---

# 2 Requirements
## 2.1 Highlevel requirements
| ID | High Level Requirements |
| -------- | -------------- |
| HLR1 | Car doors locking shall be done using wireless device | 
| HLR2 | Car doors unlocking shall be done using wireless device |
| HLR3 | Device shall be provided with wireless alarm activation and deactivation |
| HLR4 | Device shall be provided with wireless light activation |

## 2.2 Lowlevel requirements
| ID | Low Level Requirements |
| -------- | -------------- |
| HLR1_LLR1 | While pressing __Button__ all led's shall be on along with locking of doors | 
| HLR2_LLR2 | While pressing __Button__ all led's shall be off along with unlocking of doors |
| HLR3_LLR3 | While pressing __Button__ all led's shall be on in clockwise manner along with activation of alaram |
| HLR4_LLR4| While pressing __Button__ all led's shall be off in anti-clockwise manner |

---
# 3 Design and Architecture


## 3.1 Usecase Diagram

![usecase](https://user-images.githubusercontent.com/46900710/157756709-9a374505-7248-4ed9-a677-273292f3a44b.JPG)
---
## 3.2 Behavioural Diagrams
### 3.2.1 High Level Requirement Flowchart
![hlr](https://user-images.githubusercontent.com/46900710/157750487-4167fd57-70d2-4618-be12-004a04cfe271.JPG)
                        figure a

### 3.2.2 Low Level Requirement Flowchart
![llr](https://user-images.githubusercontent.com/46900710/157752943-9c907ccb-e97c-47ba-bcd2-27cdb8b81f50.JPG)
                 figure b

### * Explanation
Above figures figure a and figure b says that, The remote having many features like whenever user pressed remote button one time then all led's will be on along with locking of car doors , If user pressed remote button two times then all led's will be off along with unlocking of car doors. While pressing remote button three times then all led's shall be on in clockwise manner along with activation of alaram, If user pressed remote button four times then all led's will be off in anti-clockwise manner.

---
## 4_Test Plan

## 4.1 Highlevel testplan 

|Test ID | Description | Input | Expected Output | Actual Output | Status|
| -------- | ------------- | ---------------------- | -------------- | ---------- | -------------- |
| HLR1 | Car doors locking shall be done using wireless device| User button press | Car doors locked | Car doors locked |  |
| HLR2 | Car doors unlocking shall be done using wireless device | User button press | Car doors unlocked | Car doors unlocked | |
| HLR3 | Device shall be provided with wireless Alarm activation and Deactivation | User button press | Alarm activated/deactivated | Alarm activated/deactivated |  |
| HLR4 | Device shall be provided with wireless light activation and Deactivation | User button press | Approach lights on | Approach lights on |  |


## 4.2 Lowlevel testplan

|Test ID | Description | Input | Expected Output | Actual Output | Status|
| -------- | ------------- | ---------------------- | -------------- | ---------- | -------------- |
| HLR1_LLR1 | LED's ON | User button press | ON LED's | ON LED's |  |
| HLR2_LLR2 | LED's OFF | User button press | OFF LED's |  OFF LED's |  |
| HLR3_LLR3 | ON LED's in clockwise | User button press | LED's ON in clockwise | LED's ON in clockwise | |
| HLR4_LLR4 | OFF LED's in anti-clockwise | User button press | LED's OFF in anti-clockwise | LED's OFF in anti-clockwise |  |

---




