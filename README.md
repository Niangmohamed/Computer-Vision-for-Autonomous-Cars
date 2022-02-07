# Computer Vision for Autonomous Cars

**Author: Mohamed Niang, ML Scientist**

## Introduction

<p align='justify'> In order to put the project in its overall context and understand some important and necessary notions about autonomous cars, you must do some research and answer the following questions: </p>

* What is an **autonomous cars**? What are the different **levels of autonomy**?

* What is a **connected cars**?

* What are the **existing systems**? 

* What are the **algorithms**, **approaches** and **libraries** used actually?

### What is an autonomous car? What are the different levels of autonomy?

---

<p align='justify'> We can distinguish 6 levels of autonomy. </p>

<div align="center">

| Level 0  | No Automation          |
| :------- | :--------------------- |
| Level 1  | Driver Assistance      |
| Level 2  | Partial Automation     |
| Level 3  | Conditional Automation |
| Level 4  | High Automation        |
| Level 5  | Complete Automation    |
  
</div>

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

<p align='justify'> In 2019, Tesla cars come standard with advanced hardware capable of providing Autopilot features, and full self-driving capabilities through software updates designed to improve functionality over time. The originality within Tesla, is that it uses neither radar nor lidar, but only computer vision to solve the problem of autonomous driving.  This <a href="https://www.youtube.com/watch?v=ZiHCpeFzPgM">video</a> provides explanations on why Tesla abandoned lidar and radar to focus solely on vision by Andrej Karpathy, the Senior Director of AI at Tesla.</p>


<p align='justify'> The tesla autopilot includes in-house data labeling, neural network training, the science of making it work, and deployment in production running on our custom inference chip. Today, the Autopilot increases the safety and convenience of driving, but the team's goal is to develop and deploy <a href="https://www.youtube.com/watch?v=tlThdr3O5Qo">Full Self-Driving</a> for their rapidly growing fleet of millions of cars. In Aug 2021,<a href="https://www.youtube.com/watch?t=2900&v=j0z4FweCy4M&feature=youtu.be">Tesla AI Day</a> provides the most detailed and up-to-date overview for their amazing work. Since Tesla is currently at level 4, Elon Musk, the CEO of Tesla, said in a tweet that Tesla will fully achieve Level 5 in autonomous driving this year (2022), another big challenge for Tesla.</p>

### What are the algorithms, approaches and libraries used in previous works?

---

<p align='justify'>The table below presents a summary of some algorithms and libraries used in previous works.</p>

<div align="center">

| Object Detection | Algorithms | Segmentation, RCNN, YOLO, RNN |
| :--- | :--- | :--- |
|  | Libraries | OpenCV, TensorFlow, Pytorch |
| Object Tracking | Algorithms | KLT, CNN, RNN |
|  | Libraries | OpenCV, TensorFlow, Pytorch |
| Lane Detection | Algorithms | RCNN, DNN |
|  | Libraries | OpenCV, TensorFlow, Keras, Pytorch |
  
</div>


<p align='justify'> An example of how Tesla used neural networks for autonomous driving before. The networks learn from the most complicated and diverse scenarios in the world, iteratively sourced from our fleet of nearly 1M vehicles in real time. A full build of Autopilot neural networks involves 48 networks that take 70,000 GPU hours to train 🔥. Together, they output 1,000 distinct tensors (predictions) at each timestep. </p>

<p align="center">
  <img src="https://github.com/Niangmohamed/Computer-Vision-for-Autonomous-Cars/blob/3e7c12dfe8cc0928719c499ac6449643f78ad3d4/videos/network.gif" />
</p>

### The problems and constraints for autonomous cars?

---

<p align='justify'> Progress in autonomous car is made every day to achieve its realization. However, there are still many problems to be resolved in order to achieve a safe and sure result that takes into account all pedestrians and especially the most vulnerable. </p>

<p align='justify'> Indeed, detecting and understanding the behavior of a human being from the point of view of the autonomous car is essential for it to make the right decisions. A simple solution is to stop as soon as the situation becomes critical or when a pedestrian is close to the car. This solution remains far from satisfactory in terms of efficiency and quality of service. </p>

<p align='justify'> The resurgence of neural networks over the past 10 years due to the explosion of computing capacity brought by GPUs today provides new solutions to address certain problems that can not be solved by classical approaches. These solutions include classifiers, estimators, which use complex inputs and which are able to predict the nature of the object or indicators impossible to define otherwise. </p>

### So what is moving object detection in video?

---

<p align='justify'> Moving objects detection in video streams is a commonly used technique in many computer vision algorithms. The detection becomes more complex when the camera is moving. The environment observed by this type of camera appeared moving and it is more difficult to distinguish the objects which are in movement from the others that composed the static part of the scene. </p>


<p align='justify'> The study of the different motion detection methods proposed in the literature has allowed us to notice that most of the proposed solutions consist of considering video sequences as successions of images, generally classified into two categories: the current image , and the past. The most common approach is to build a more or less compact model that is supposed to represent all the past, and to confront the current image with this model in order to decide in any point, if it represents the background or a moving object. </p>

## Detection and tracking of moving objects using background segmentation

<p align='justify'> The purpose of this section is to detect and track moving objects in sequences with dynamic background using background segmentation. </p>

### So what is Object Detection/Tracking?

---

<p align='justify'> In object detection tasks, we want to find all objects in the image and draw bounding boxes. Autonomous car in real-time video stream is an excellent example of object detection, where it is necessary to find the location of other cars, traffic lights, road signs, humans, ... </p>

<p align='justify'> Video tracking is the process of locating a moving object or multiple objects over time using a camera. Video tracking can be a time consuming process due to the amount of data that is contained in video. </p>

<p align='justify'> Now that you know what is object detection, tracking and background segmentation let’s do some coding. Open the specific notebook for this part in the project folder. At the end, you have to obtain something like this. </p>

<p align="center">
  <img src="https://github.com/Niangmohamed/Computer-Vision-for-Autonomous-Cars/blob/283d831b9823787693ec7ee9b7b4904214e4a9d5/images/segmentation.png" />
</p>

## Detection of moving objects using LIDAR

### What is Lidar technology? What is the importance of Lidar in autonomous cars?

---

<p align='justify'> Light Detection and Ranging (LIDAR) is a remote sensing method used to measure a distance from a laser beam emitted on an object or in the atmosphere. Hundreds of thousands of points are generated several times per second for a range of several hundred meters. The lidar delivers an accurate measurement of the distance from each point on which the laser is reflected as well as an intensity of the received signal (represented in the image below by a color). The resolution of the lidar depends on the number of channels or layers (lines traced by the laser), which range from 4 to 256. </p>

<p align="center">
  <img src="https://github.com/Niangmohamed/Computer-Vision-for-Autonomous-Cars/blob/main/images/lidar.png" />
</p>

