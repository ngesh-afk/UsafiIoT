# UsafiIoT
WaziHub Innovation Competition Project Proposal Guide<br/>
Usafi IoT-TechNawa (Smart hand washing system) <br/><br/>
<b><h3><u>1. Team Composition</u></h3></b>
Kamau Solomon	Embedded system Programmer.(Leader)	Solomonkamau19@gmail.com	+254710719728<br/>
Henry Muchunga	Lead Engineer	emailtomuchunga@gmail.com	+254725590011<br/>
Linet Kiunga	Software Developer	Lkiunga542@gmail.com	+254748115393<br/>
Willy Kimanzi Software Developer willycubekimanzi@gmail.com +254797351448</br>
<b><h3>2. Introduction</b></h3><br/>
<b><h3>Problem statement.</h3></b><br/>
The spread of Corona Virus is caused by touching surfaces with this virus. This virus is then spread from one person easily without human being even indicating any symptoms of Covid -19 disease that is caused by the virus. One way to stop this disease from spreading is through regularly washing hands with running water and soap. 
From our point of view, the way the exercise of washing hands is being done might not stop the spread of the virus. This is because when people are washing hands especially in public places, where the government or organization have put aside tanks for people to wash hands at, are using taps which people have to touch to let water run out of the tank. 
When a person with the virus first touches the tap surface with their hands, they leave the virus there, washes their hands and touches the tap again coming into contact with the virus. When a second person with no virus comes to use the same tap, they will carry with them the virus by the end of the exercise.  This made us feel that to fully combat this disease that has affected the whole world, we should automate the manual taps with the automated ones.<br/>

<b><h3>Stage of the project.</h3></b><br/>
The project is at prototyping phase. 
<b><h3>Proposed Solution.</h3></b><br/>
Teck Nawa (Smart hand washer system) is an automated hand washing system that will replace the already existing smart hand washing taps to reduce contacts of physical parts hence reducing the spread of Covid-19 (coronavirus) disease. This is a device that will improve the efficiency of washing hands. The device has key advantages such as low power consumption, portability and easy implementation steps. This model has championed for
reliability, accuracy and scalability at the same time.
An additional value about the device is that it can be implemented in new water stations or
already existing ones with ease. The device is intended to use less power which means it can be used with a miniature solar panel, electricity or battery pack. In the end it is therefore expected to be
portable, low cost and power effective solution that can be used to power the device without any
issues.
There are parameters that will be collected by the device such as frequency of washing hands, water level in the tank as well as temperature and humidity of the environment where the device is. This data will help in terms of making sure the tank is readily filled with or containing a volume of water enough to serve a certain period of time, know where the exercise of washing hands is high or low and finally to know whether weather change affects the action of washing hands. This data will be of help to government as well as private sectors who want to make sure the disease is under control.
<b><h3>3. Problem Statement</h3></b><br/>
The simple act of hand washing, is the single most cost-effective way of stopping the spread of
Coronavirus or otherwise most commonly known as COVID-19. However, the complexities
that revolve around the handwashing exercise, pose by itself a threat towards a point to point
spread of the virus itself. Some studies have shown that Sars-Cov-2, the name of the virus that
causes COVID-19 can survive on metal, glass and plastic for as long as nine days, if not
disinfected. At low temperatures, an extent of up to 28 days can be reached. These are the
exact materials that most of the taps in our homes and public places are made of.
How can you open or close a tap without touching the lever? This is the big question?
Additionally, can such systems be readily available to everyone? While electronic designs of
such nature already exists in most high-end public buildings and facilities, deterrents arise on
the exact cost of manufacture and deployment. Additionally, the scalability of such systems is
not the easiest, especially in areas that are mostly rural or with limited access to a stable
electricity connection.
It has therefore been our obligation to tackle the challenges posed through the development
of a low-cost, low-power, automated “no-touch’’ hand-washing system. By use of readily
available materials. We therefore had an idea of having a system that can solve this problem. A simple swipe of your palms across the tap’s pout triggers a voluntary action of an electronic valve to open allowing water and liquid soap onto your hands for the duration of washing exercise. The absence of your
palms cause the valve to shut automatically.
The need of this system is large as it be needed either at home for personal use and in public facilities. This device was from the idea of stopping the spread of Corona virus but it will also help combat other diseases that are spread through germs due to lack of proper hygiene. 
<b><h3>4. Goal of the Project</h3></b><br/>
The main goal of this project is to help flatten the rising cases of affected people by Corona virus as people go on with their normal life through reducing the contacts of surfaces during washing hands. The data  collected by the nodes will help a lot  making sure, necessities that are needed to help people keep washing their hands are provided including and not limited to educating the members of the public the importance of washing hands based on the data generated about where the exercise of washing hands is not embraced. 
<b><h3>5. Solution</h3></b><br/>
The device will be automated and no one will be touching surfaces while washing their hands. The device will be sensing hand palms and will be allowing liquidized soap to flow out. Every person using the system will be given time to apply soap thoroughly on their hands, after some time, water will be released out through a tap to help people rinse their hands before it switches off. The timer will be indicated by Light Emitting Diodes(LEDs) to notify people that water is almost running out so as to avoid water wastage. Data about the amount of water that has been dispensed, Level of water in the tank, Number of times tap has been opened, as well as temperature and humidity levels from the environment will be collected and pushed to the cloud using Waziup technology. 
<b><h3>6. Project Equipment </h3></b><br/>
We will design a dashboard that will be used the visualize different parameters as they are logged from the cloud. The dashboard which have processed data will aid in term of making decissions and planning about what to do for a certain area where the devices are.
To make this project a success hardware equipment will be put together to make an IoT node.
The node will consist of:  
1.	DHT 22/ DHT 11 (Temperature and Humidity sensor)
2.	Solenoid valve.
3.	2 *1 5v Single channel relay.
4.	Ultrasonic sensor.
5.	Flow Meter.
6.	JSN-SR04T water proof Ultrasonic sensor.
7.	Submissive pump.
8.	Wazidev Microcontroller Board.
9.	Waziup gateway.
10.	Copper clad board.
11.	Solar Panel .
12.	12v rechargeable battery.
13.	Dc power step up module
14.	DC-DC voltage regulator.<br/>
<b><h3>7. Project Implementation Plan</h3></b><br/>
<b><h4>Sensing and communication. </h4></b><br/>
We will require to assemble the components for a node. The node will consist of sensors and actuators that will be connected on a breadboard by Henry Muchunga, who is the team hardware engineer. The node will be programmed by Solomon Kamau to make sure all the sensors and actuators are working well and as expected. The breadboarding circuit will be thereafter transferred to a PCB ready to be packaged.<br/>

<b><h4>Data connectivity</h4></b><br/>
A waziup Gateway will be set to run to ensure that data is being pushed to the WAZIUP dashboard. Programming of the node will be done to ensure that data collected by sensors and from actuators is published on the dashboard. This will be done by Solomon Kamau.
<b><h4>Application Development</h4></b><br/>
A web-based dashboard will be developed to help visualize data logged by the node. This data will be presented in a simple way that users will be able to understand. The data will help them make decision easily a way that will help fight with the pandemic. After the development of the application, an API will be added to help fetch data from the waziup dashboard to the user’s dashboard. This dashboard will contain information such as Humidity and temperature level, Number of times the tap has been opened. Amount of water remaining in the tank as well as graph showing the relationship between weather changes and frequency of washing hands. Dashboard development will be done by Linet Kiunga with the help of team members.
<b><h4>Business Validation</h4></b><br/>
When we are done the product will be tested internally to see if its working as expected. We will evaluate the product and make sure it meets or standard. Price will be discussed and reached upon after the cost and labor used to design and produce the item is evaluated.   We will thereafter approach our target customers including Government, Individual people, private organizations among other interesting parties. Upon getting the targeted customers, we will advertise the product to ensure those interested with the product got it at a friendly price. Deployment of the item will be done after sales services as well as maintaining the product for a given period of time as we train the users on how to fix non major issues when need arises.
<b><h3>8. Business Model </h3></b><br/>
Coming at a time the world is facing the Covid-19 menace, we believe our customer base is with institutions serving people at different levels. Here we have schools, hospitals, travel terminus among many. We seek to counter the threat in places where the danger of exchange of Covid-19 virus and other disease causing agents through contact is eminent.
Our market will consist of institutions in the forefront in the fight against Covid-19. These institutions we are convinced they will find useful the data collected and channeled to Waziup platform to make appropriate changes. Here we expect the county governments, schools, hospitals, places of worship, real estate developers and private residents to form our market stronghold.<br/>
Working together, we have strengths that make us ideal. One, is that all members have different backgrounds in technology which helps us develop a perspective based on information from embedded systems, Computer Aided Design, software development and the overall effect of the recent changes implemented to curb the disease’s spread. This makes gives our team the capacity to produce a viable solution to various problems. A common challenge we face however is lack of prototyping materials arising from being forced to stay away from innovation hubs when we often used to get out work done.<br/>
Our product features essential elements including automation of taps to prevent contact with taps, also the data collection feature is crucial in doing research or making decisions related to the same, we also believe we will motivate Kenyan and African young people to gain interest in building solutions for Africa’s problems.
Majorly, we hope to sell our product directly to individuals for use at their business and private premises and making agreements with key stakeholders in the market such as government officials, real estate developers, transport service saccos, heads of schools among many. We however look forward to marketing through various media to reach out to even those that would need customized versions to fit their needs.</br>
Among the milestones we have hit, we have been able to make significant step in the automation of taps where we have developed a sample prototype, our software developer had created a functional dashboard to view incoming data from the node and finally we have our CAD specialist working on processing the prototype’s circuit board and the required 3D printed housing for the same.
