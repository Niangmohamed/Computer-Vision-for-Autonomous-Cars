# Computer Vision for Autonomous Cars

## Introduction

<p align='justify'> In order to put the project in its overall context and understand some important and necessary notions about autonomous cars, you must do some research and answer the following questions: </p>

* What is an **autonomous cars**? What are the different **levels of autonomy**?

* What is a **connected cars**?

* What are the **existing systems**? 

* What are the **algorithms**, **approaches** and **libraries** used actually?

### What is an autonomous car? What are the different levels of autonomy?

---

<p align='justify'> We can distinguish 6 levels of autonomy. </p>

| Level 0  | No Automation          |
| :------- | :--------------------- |
| Level 1  | Driver Assistance      |
| Level 2  | Partial Automation     |
| Level 3  | Conditional Automation |
| Level 4  | High Automation        |
| Level 5  | Complete Automation    |

**Level 0: No Automation**

<p align='justify'> The driving is entirely the responsibility of the driver who may have warning mechanisms such as the sound signal when crossing line. </p>

**Level 1: Driver Assistance**

<p align='justify'> The driver is always responsible for the maneuvers, but delegates some of the tasks to the system. He must be able to fully regain control over driving if the situation requires it. </p>

**Level 2: Partial Automation**

<p align='justify'> The responsibility for the maneuvers is entirely delegated to the system, but everything is done under constant supervision of the driver, who can decide to take back the hand at any time, for example during an automatic lane change or parking assistance which is activated only when a parking space is detected or selected by the driver. </p>

**Level 3: Conditional Automation**

<p align='justify'> The driver may delegate the driving on the two guiding dimensions (longitudinal and lateral) and can lower his level of vigilance to focus briefly on other tasks. The intelligent steering system then takes care of positioning and maintaining the vehicle on its way while maintaining a rhythm adapted to the speed and traffic conditions. The driver must remain able to regain control of the operation if the conditions require it. </p>

**Level 4: High Automation**

<p align='justify'> The driver no longer intervenes and can indeed completely divert his attention to do something else. On the other hand, this level concerns only certain driving modes and under certain conditions. It is the driver who activates and deactivates the automated mode. </p>

**Level 5: Complete Automation**

<p align='justify'> The human being does not intervene any more neither in the control nor in the supervision of the task of driving. Everything is under the responsibility and control of the system. The presence of a human being at the controls is no longer necessary. Let’s see the video in this <a href="https://www.youtube.com/watch?v=xsQvq4WlUYU">link</a> that describe the 6 levels of autonomy with an example of BMW autonomous cars. </p>

### What is a connected car?

---

<p align='justify'> A connected car integrates wireless telecommunications systems that allow it to collect information that it can record, process, operate and relay to other vehicles, or send to the road infrastructure. The data collected by the car are numerous and varied. Some are related to flight, such as distance information with another vehicle measured by a radar. Other data concerns the life on board, for example the transfer of music stored on a smartphone or a film … Since 2017, on the decision of the European Union, all new car must be connected in order to automatically make an emergency call in case of an accident: this is the e-Call service. By 2020, it is estimated that 80% of cars will be connected. </p>


### Study of the existing!

---

<p align='justify'> Google car, called Waymo since 2016, is an electric car designed entirely by Google without steering wheel neither accelerators controls. The giants of digital field have been pioneers in the development of autonomous cars. Since the arrival of the Google Cars in 2009, the tests carried out by different companies are multiplying, in the United States, Asia or Europe. In California, one of the most advanced US states on the issue, 27 companies have filed an application for authorization to test their vehicles on state roads. Some, like Valeo working on Level 3 autonomy solutions, have developed their own prototype. For their part, mobility players such as the leader in Uber VTC are also preparing for the future. The development of a complete and operational system based on autonomous and connected vehicles is not feasible by a single actor. None can control all its components. </p>
  
<p align='justify'> The trend, which is only accelerating is alliances and even mergers between operators, builders and public and private research organizations. car manufacturers are establishing partnerships with transport operators, such as Renault with Transdev, or German manufacturers with operators in major cities such as Hanover, Stuttgart and Munich. In addition, car manufacturers buy specialized companies at gold prices. GM has offered Cruise Automation, which has developed an autonomous driving system, for about a billion dollars. Ford will invest the same amount in the start-up Argo-AI. As for German manufacturers Daimler, BMW and Audi, they bought for 3 billion dollars, the provider of geographical maps Here.</p>

<p align='justify'> The big digital firms are doing the same. The Google Car project gave birth to a commercial subsidiary, Waymo, which has partnered with Honda and Fiat-Chrysler. Apple has invested a billion dollars in Didi Chuxing, China’s autonomous car platform. Uber, for 680 million dollars, has acquired Otto, which transforms trucks into autonomous vehicles. Not to mention Microsoft’s partnerships with Toyota, Renault Nissan and Volvo. </p>

<p align='justify'> In 2022, Cruise’s driverless car division plans to launch a completely automated taxi service in San Francisco. Cruise has already started testing self-driving cars in the city, picking up General motors employees for test drives without someone in the front two seats. </p>

<p align='justify'> Pony.ai began testing self-driving cars on public highways in California in June 2021, with ambitions to provide commercial service in 2022. In 2020, Uber sold its self-driving vehicle section to Aurora Innovation Inc. and acquired a share in the company, abandoning its plan to build a fleet of self-driving taxis. The Uber Eats trial programme will deliver meal packages from select restaurants in the Santa Monica region of Los Angeles via the Uber Eats app. By early 2022, Uber Eats customers will be able to buy restaurant meal kits and have them delivered by one of Motional’s modified all-electric Hyundai Ioniq 5 robotaxis. The Hyundai cars employed in the testing had never been used to deliver anything before. </p>

<p align='justify'> In 2019, Tesla cars come standard with advanced hardware capable of providing Autopilot features, and full self-driving capabilities—through software updates designed to improve functionality over time. The originality within Tesla, is that it uses neither radar nor lidar, but only computer vision to solve the problem of autonomous driving.  This <a href="https://www.youtube.com/watch?v=ZiHCpeFzPgM">video</a> provides explanations on why Tesla abandoned lidar and radar to focus solely on vision by Andrej Karpathy, the senior director of AI at Tesla.</p>

