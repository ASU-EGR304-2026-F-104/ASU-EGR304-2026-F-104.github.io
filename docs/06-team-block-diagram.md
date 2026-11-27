---
title: Team Block Diagram
---

## Introduction: Team Block Diagram for HaMaLoYa Team 104
The block diagram follows the wheel and spoke design, with subsystem 2 - Logan's block - acting as the center of the wheel. The design is set up so there can be two sensors to detect a drowsy driver and two actuators to alert the user. The first subsystem is a photoresistor, detecting how light the surrounding area is. This will help the device detect nighttime as to avoid false alerts during the day. The second subsystem has an accelerometer to detect any jerky motions, like a driver falling asleep. The third subsystem uses a speaker to make a loud noise and keep the driver awake. The final subsystem uses a motor to cause haptic feedback and wake the user up. The wheel and spoke design was chosen so there can be two different checks with the sensors before both actuators go off at the same time.

The ribbon connections are numbered based on which spoke of the wheel they connect. Connection 1 is between Hannah's and Logan's boards, with an analog signal going through pin 7. Connection 2 is between Logan's and Matthew's boards, with a digital signal going through pin 3. Connection 3 is between Logan's and Yazmin's boards, with a digital signal going through pin 1. All pin 8s are connected to a unified ground to keep the system from short circuiting.

## Team Decision Making Process
(discuss team's design and decision making process related to message structure REPLACE THIS SECTION WITH ANSWER)

## List of top 5 Changes
(Numbered list of the top 5 biggest changes to your software design since the software proposal. Include several sentences for each change describing the issue and how you resolved it. Use the UML diagrams above to support the discussion. REPLACE THIS SECTION WITH ANSWER)


## Block Diagram Image
<img width="4162" height="864" alt="TeamBlockDiagram11-25 drawio" src="https://github.com/user-attachments/assets/319dcc76-def7-4f6c-95ef-234e5ddd4e3f" />
<!--
<img width="4162" height="864" alt="BLOCK" src="https://github.com/user-attachments/assets/1afb3329-80c4-448a-8f79-23bb4dbeb890" />
-->

## Markdown
[Download the Draw.io source file](https://github.com/user-attachments/files/35443942/TeamBlockDiagram11-25.pdf)
<!--
[Download the Draw.io source file](https://github.com/user-attachments/files/34144135/BLOCK.1.pdf)
-->


## Team Connection Tables

_**Table 1.0**: Team connection between Hannah and Logan_

| Pin | From | To | Type | Description |
| :------: | :----: | :----: | :----: | :----: | 
| 1 | - | - | 0V - 5V Digital | Not used | 
| 2 | - | - | 0V - 5V Digital | Not used | 
| 3 | - | - | 0V - 5V Digital | Not used |  
| 4 | - | - | 0V - 5V Digital | Not used | 
| 5 | - | - | 0V - 5V Digital | Not used | 
| 6| - | - | 0V - 5V Analog | Not used | 
| 7 | Hannah (RA1) | Logan(RA0) | 0V - 5V Analog | Photoresistor output <br> signal |  
| 8 | GND | GND | GND | GND | GND | 


_**Table 1.1**: Team connection between Logan and Matthew_

| Pin | From | To | Type | Description |
| :------: | :----: | :----: | :----: | :----: | 
| 1 | - | - | 0V - 5V Digital | Not used |  
| 2 | -| Matthew (RA4) | 0V - 5V Digital | Not used |  
| 3 | Logan (RD2) | - | 0V - 5V Digital | Motor activation <br> signal | 
| 4 | - | - | 0V - 5V Digital | Not used | 
| 5 | - | - | 0V - 5V Digital | Not used | 
| 6| - | - | 0V - 5V Analog | Not used | 
| 7 | - | - | 0V - 5V Analog | Not used |  
| 8 | GND | GND | GND | GND | 


_**Table 1.2**: Team connection between Logan and Yazmin_

| Pin | From | To | Type | Description |
| :------: | :----: | :----: | :----: | :----: | 
| 1 | - | - | 0V - 5V Digital | Not used |  
| 2 | - | - | 0V - 5V Digital | Not used | 
| 3 | - | - | 0V - 5V Digital | Not used |  
| 4 | Logan (RF1) | Yazmin (RB2) | 0V - 5V Digital | Speaker activation <br> signal | 
| 5 | - | - | 0V - 5V Digital | Not used |
| 6| - | - | 0V - 5V Analog | Not used | 
| 7 | - | - | 0V - 5V Analog |  Not used | 
| 8 | GND | GND | GND | GND | GND | 
