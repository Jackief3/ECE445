# Jackie Fang

- [Jackie Fang](#Jackie-Fang)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)

## 2025-01-27 - Project Ideas
Here are the project ideas we brainstormed on this day.
Haokai:
Battlebot
Laser Cat Toy

Jackie:
Water Quality Management System

## 2025-01-29 - WebBoard Post
We met in ECEB Undergraduate Student Lounge on the 3rd floor to brainstorm about our project. We decided to use an ESP32 microcontroller and have the sensors and the microcontroller powered by a rechargeable battery that was rechargeable through solar power. The sensors we thought of using were testing for conductivity, ph, turbidity, and temperature.

## 2025-02-01 - Initial WebBoard Idea Post
We met to make a finished idea post for our water quality management system. Things we put into the idea post: problem, solution, the sensors for our system, the subsystems in the project, communication between the MCU and the sensors, and the criteria for a successful project. Our problem is that water pollution is a growing issue. Our solution was a low-cost IoT-based water quality management system designed to provide real-time data. We researched the different types of sensors we would use in our design. These are the sensors we came up with for our initial project idea: pH Sensor: 5016-SRV-PH-ND Turbidity Sensor: 1738-1185-ND Liquid Temp Sensor: Digikey 480-2016-ND TDS Sensor: DigiKey 1738-1368-ND. We decided that bluetooth capability from the ESP32 to access the data would be better than wifi from the ESP32. We also added the criiteria for the success of our project to be accuracy of sensors within 5% error, real time data transmission every 30 minutes with little to no data loss, keeping the project under $150, and last 24 hours on battery and solar power.


## 2025-02-03 - Edit to WebBoard Idea Post
We added DigiKey 1738-1368-ND Dissolved oxygen sensor: dissolved oxygen meter as a sensor to our project.

## 2025-02-05 - Final Edit to WebBoard Idea Post
We met with a TA to finalize our project idea. We decided not to use solar power. Reframed the application of our project to be geared towards aquatic life, whether it is fish farms or fish tanks.

## 2025-02-08 - Team Contract and Project Proposal
Project was approved on the WebBoard. We met to work on the team contract and project proposal document. We made a general outline of the project proposal document using most of the same things on the WebBoard idea post.

## 2025-02-11 - First TA Meeting
As a group, we met with Rui for the first time. Rui gave us reminders on what needed to be done in the upcoming week, and we gave him an update on what we have done so far. (project proposal outline and team contract)

## 2025-02-13 - Project Proposal and Parts List
Met with my group and finished up the project proposal document. I added ethics and safety to the document. We added block diagram and created a new document called Tentative Parts List where we did research and put in the sensor parts that we were planning on using. The different temperature sensors Harry added into the list are: Digikey 480-2016-ND, Digikey 1738-1311-ND, Digikey 1528-1592-ND. I added Digikey 5016-EZO-DO-ND for our Dissolved Oxygen Sensor. I added 1738-1195-ND for our Turbidity sensor and SEN0244 for our TDS sensor list.

## 2025-02-14 - First Machine Shop Visit
With my group, we introduced the Water Quality Management system project to the machine shop, and got feedback and design ideas. They told us that they were able to help us and that it would not be too difficult.

## 2025-02-17 - Proposal Review
We pitched our project to a group of peers and Professor Gruev. We got feedback on our project proposal from both the TAs and Professor Gruev. Professor Gruev told us that our project seemed too simple and to make it more complex. Some added complexity ideas we talked about are future data prediction, be able to submerge the system in water, and make the project solar powered.

## 2025-02-23 - Group Meeting through Discord Call
Talked about revising our proposal to include future data prediction as a bonus to the project. We also talked about what sensors we planned on using for the project. We chose Digikey 480-2016-ND for the temperature because it was marked available in the ECE lab room. This is what it looks like: 
![image](https://github.com/user-attachments/assets/df471682-2c89-43c1-a3c0-aca3a84f1519)

For the dissolved oxygen sensor, we chose Digikey 5016-EZO-DO-ND. For turbidity, we were talking about 1738-1195-ND. For the ph sensor we talked about 5016-SRV-PH-ND. For the total dissolved solids, we talked about SEN0244. We also started designing the circuitry for each of the sensors. I designed the circuitry for the power system. The power system has two voltage regulators and two voltage inverters. Each of the voltage regulators are there to step down a 9V load to a 3.3V or a 5V load. The volatage inverters are there to invert the stepped down voltages to the voltages we need for the other sensors. The following is an image of the schematic for our power subsystem: 

## 2025-02-25 - Weekly TA Meeting
We had our weekly meeting with Rui. We gave him an update of our current project progress. Rui gave us a reminder that the first round of PCB orders are due next week on March 3rd and that on Friday, there will be TAs to help with designing the PCB. 



































