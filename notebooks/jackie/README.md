# Jackie Fang

- [Jackie Fang](#Jackie-Fang)
- [2025-01-27 - Project Ideas](#2025-01-27---Project-Ideas)
- [2025-01-29 - WebBoard Post](#2025-01-29---WebBoard-Post)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- [2025-01-27 - Project Ideas](#2025-01-27---project-ideas)
- 


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

For the dissolved oxygen sensor, we chose Digikey 5016-EZO-DO-ND. For turbidity, we were talking about 1738-1195-ND. For the ph sensor we talked about 5016-SRV-PH-ND. For the total dissolved solids, we talked about SEN0244. We also started designing the circuitry for each of the sensors. We also did research on the different sensors.

## 2025-02-25 - Weekly TA Meeting
We had our weekly meeting with Rui. We gave him an update of our current project progress. Rui gave us a reminder that the first round of PCB orders are due next week on March 3rd and that on Friday, there will be TAs to help with designing the PCB. 

## 2025-02-27 - Proposal Revision
Today, we revised our proposal to include the future data prediction for our project. We also researched on other sensors and looked if there were any other outside sources that have schematics done for the sensors. 

## 2025-03-02 - Weekend Meeting
We continued designing the PCB and did research on the sensors and how they worked. I confirmed with my team that we are not using development boards for our sensors. Originally, we selected development boards for our sensors. I designed the circuitry for the power system. The power system has two voltage regulators and two voltage inverters. Each of the voltage regulators are there to step down a 9V load to a 3.3V or a 5V load. The volatage inverters are there to invert the stepped down voltages to the voltages we need for the other sensors. The following is an image of the schematic for our power subsystem: <img width="406" alt="image" src="https://github.com/user-attachments/assets/4163eee0-f68c-4550-a6c0-458704fbc56a" />

I also worked on integrating the schematic for the dissolved oxygen sensor into our design. The following image is the schematic for the dissolved oxygen sensor: ![image](https://github.com/user-attachments/assets/c81800c8-28d6-4e96-8cad-8d6ac0d53cc7). DFRobots is the source for this schematic. I also worked on the initial schematic of the ESP32. This is what it looks like: ![image](https://github.com/user-attachments/assets/4db21679-45bf-4363-a136-57d29f9c8b21)

## 2025-03-03 - Schematic Design Complete
We finished the design on the schematic today. ![image](https://github.com/user-attachments/assets/654c9881-0630-4ad4-a6d0-2bf55854f6f8)
We added more components into the parts list. The components we added are op amps, voltage inverter, voltage regulator, and some resistors. Harry also put in orders for our sensors.

## 2025-03-04 - Weekly TA Meeting
Today we met with Rui and gave him an update on the project. Rui reminded us that the Teamwork evaluation assignment was due March 5th and the Design Document due March 7th. He also reminded us that the breadboard demo was next week and that there was no weekly meeting that week.

## 2025-03-04 - Started The Design Document
I started on the design document and copied the proposal document over to the design document.

## 2025-03-05 - First PCB Design Complete
Haokai finished designing the PCB. This is what it looked like: ![image](https://github.com/user-attachments/assets/b6cfe350-11b8-4c44-a7a9-fdf20da2ae82)

## 2025-03-06 - Finished the Design Document
Finalized the list of parts we need and where each of those parts are going to be obtained. We also finished the design document. In addition to what I did before for the design document, I created the tentative schedule for the rest of the semester for our group.

## 2025-03-11 - Weekly TA Meeting
I started the breadboarding for the breadboard demo today. We met with Rui and gave him an update on how the project is going and that we are in the middle of breadboarding our project. Rui reminded us that the second round of the pcbway order is due on Thursday. I made a lot of trips down to the Eshop to get parts for our breadboard. I had some trouble breadboarding the voltage regulator to work. I finished breadboarding the temperature sensor and managed to get a voltage regulator working. We did not have any development boards with us, so I borrowed an ESP32 development board from a friend. We could not get it working so I borrowed another friend's arduino breadboard: ![image](https://github.com/user-attachments/assets/033408f0-cf4d-4735-9f09-4ebe9daf2d34)

## 2025-03-12 - Breadboard Demo
Today, we demoed what we have to our professor and ta. I showed the voltage regulator working by measuring the voltage across the output and ground. We showed the temperature sensor working by holding it in our hands to show the increase in temperature. I explained that we couldn't get the ESP32 development board to work, so we got a different development board to work. Professor Gruev asked Harry about how the code works and how the values of temperature were obtained. Professor Gruev also asked me what voltage the Arduino development board takes to which I didn't know the answer to. The professor also asked me how the BNC connection would work and I told him how one of the connections would be to ground and the other would be to the circuit. I let the professor know we were having trouble getting a dissolved oxygen sensor for the right price. I also let the professor know that the Turbidity sensor is on backorder and won't be here anytime soon.

## 2025-03-13 - Second Order for PCBs
We had issues with passing the audit for the PCB and could not make the 2nd order deadline.

## 2025-03-14 - Gerber File Passed
Haokai fixed the issue and the Gerber file passed the audit. We plan on submitting it for the 3rd PCB Round

## 2025-03-25 - Weekly TA Meeting
Rui reminded us that the 3rd round for the the PCB orders was next week. We also gave him an update on our project and that we were having difficulty with locating a low-cost dissolved oxygen sensor.

## 2025-04-01 - Weekly TA Meeting
We updated Rui on our progress for the project. Rui reminded us that the individual progress report was due Wednesday and that the 4th round of pcb is due next Monday.

## 2025-04-07 - Digikey Order
Haokai made orders for resistors, capacitors, and other components like op amps and voltage inverters that we don't have yet. Haokai also order the esp32 development board.

## 2025-04-08 - Weekly TA Meeting
We gave Rui an update on the project. I told Rui that we have some issues with the PCB, and he told us that we would need to make the order ourselves through PCBway. I realized we don't have a way to code the ESP32 once it is on the board. We also did not have a way to plug in our battery. Haokai ordered the wrong ESP32. He ordered the chip instead of the development board.

## 2025-04-10 - PCB Order arrived
Our first PCB order arrived. Our initial design did not have a way for us to code it.

## 2025-04-13 - Group Meeting
We fixed our PCB issue of not having an area for the battery to be plugged in. Also, we added a micro USB B so that we can program the ESP32. We also added buttons for the EN and RST pins of the ESP32 and pulled them high so that those pins turn on only when the button is pressed. 

## 2025-04-14 - Meeting with Rui
I met with Rui to have our PCB schematic and design checked. We talked about the schematic for the buttons, USB, and the power for the ESP32. I also talked with my group, and we discussed whether we needed a CP2102 chip in our design. The chip is used to help with USB-Serial for the ESP32. We decided not to get/use the chip because our micro USB B is going to be native on the PCB.

## 2025-04-15 - Weekly TA Meeting
Rui helped us confirm our PCB design, specifically the USB B and the EN and RST pins. Rui reminded us that the Mock Demo is next week.

## 2025-04-16 - Final PCB Order Made
Haokai made the order for the PCB.The following image is our final schematic design. ![image](https://github.com/user-attachments/assets/f17690dd-1b90-4718-aa2f-9685e6dbe5a5)
The following image is our final pcb design.![image](https://github.com/user-attachments/assets/8620f34f-9e2d-4e53-9d32-1d26bd65ab53)

## 2025-04-18 - Machine Shop Visit
I visited the machine shop and asked them to make a mount for our PCB. I gave them our old PCB because it is the same size as the new one. I was able to pick up the mount on the same day. I soldered the temperature sensor circuit and the 3.3V voltage regulator circuit onto the old PCB.

## 2025-04-19 - Preparation for Mock Demo
I soldered on wires onto the old PCB and connected it to the breadboard where I have the ESP32 breadboard. There, we checked that the temperature sensor was function as intended from the PCB.

## 2025-04-21 - Preparation for Mock Demo
I soldered the ESP32 development board to the PCB for the Mock Demo. After the mock demo, I desoldered the ESP32 development board from the PCB. We also double checked that we had all the necessary parts. We were missing some parts so I put in the order for capacitors, resistors, potentiometer, and op amps. I also coded the PH sensor on the Arduino IDE. This code will be uploaded as PHsensor.txt in my directory.


## 2025-04-25 - Final PCB Arrived
Haokai started soldering the final PCB.


## 2025-04-26 - Soldering the Final PCB
Our final PCB came in and I checked that Haokai's soldering was not good so I grabbed a new PCB and started from scratch.![image](https://github.com/user-attachments/assets/c16931a7-cc61-4540-85d9-a0896cdfd485)
![image](https://github.com/user-attachments/assets/8f492287-4abc-43f5-9a88-0acf6879d91a)
I soldered on the ESP32 chip, micro USB B, and op amps. <img width="385" alt="image" src="https://github.com/user-attachments/assets/7668591b-1161-4c1d-b2d7-c509c0c7c40f" />

## 2025-04-27 - Soldering the Final PCB
I finished soldering our final PCB. I soldered on the resistors, capacitors, and most of the through-hole components. ![image](https://github.com/user-attachments/assets/b1972968-d3c5-4ba8-8f8a-55e186807786)

## 2025-04-27 - Testing the Final PCB
We tested the final PCB and the only sensor that worked is the temperature sensor. The other sensors had issues outputting the data. I suspect it is because we do not have the CP2102 chip to help convert micro USB B data to serial to the ESP32. We used the digital multimeter in the lab to check the outputs and inputs of each of the sensors' voltage, and the data was all within the range voltage of 3.0-3.6 volts. I then doubled check my soldering for each of the components and found nothing wrong.

## 2025-04-28 - Final Demo
I then looked at our design and noticed that there was nothing powering the ESP32, so my solution was to solder on the development board like I did for the mock demo. I soldered the development board onto the PCB, but the sensors still did not work as intended. We ran out of time and demoed what we had. The demo did not go well.

## 2025-05-01 - Creation of the Final Presentation
We met at DCL to work on the presentation slides for the Mock Presentation. We finished the slides for the mock presentation which means that we only had a few more slides to add for the final presentation.

## 2025-05-02 - Mock Presentation
We had our mock presentation today. It was good practice, and the feedback we received was good. The feedback we got was to not read off the slides, try to make the slides more appealing by having fewer words, and add more pictures of our project into the slides.

## 2025-05-04 - Editing the Presentation Slides
We added more to the presentation slides for our final presentation.

## 2025-05-05 - Final Presentation
We finished the presentation slides for our final presentation. We had our final presentation today. It went really well compared to the Final Demo. I did not stutter as much and enjoyed presenting to the audience.

## 2025-05-07 - Final Paper
We wrote the final paper today. It consists of a title page, abstract, introduction, design procedure, design details, verification, cost analysis, conclusion, references, and appendices.
