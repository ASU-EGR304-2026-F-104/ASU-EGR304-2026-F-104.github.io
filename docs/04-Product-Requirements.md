---
title: Product Requirements
---

## Project Objective

This project aims to design and develop an awareness device for drivers who may experience drowsiness and fatigue. The product will have a system with components that include an audible buzzer, flashing LED, actuator, and motion sensor that will all trigger a response to alert the driver if they start experiencing fatigue or drowsiness. The product is planned to be convenient, compact, rechargeable, and easy for the driver to use. 

| Objective | Specifics | Units |
|-----------|-----------|-------|
| Battery life | Should last 8 hours minimum, have a rechargeable feature | Hours |
| Size | Should not exceed 11in x 5in x 4in | in |
| Weight | Should not exceed 5 lbs | lbs |
| Visually Appealing | Should make at least 75% of the customers rate the product visually appealing | percentage of positive reviews on aesthetic of product|
| Buzzer alarm | Reacts to motion sensor to trigger buzzer for user to stay awake | Decibels |
| Motion sensor | Should detect head movement, if head is within 10 cm of sensor, will trigger assuming the driver is falling asleep | cm |
| LED | Reacts to motion sensor to trigger flash to alert the user to stay awake | Lumen |
| Actuator | Should tap the driver to wake them up by rotating from 0 to 90 degrees and 90 to 180 degrees | Degrees |
| 5V Regulator | Should maintain an output voltage of 5V to the system | Volts |


## Stakeholders

* **Target group** Drivers who spend long hours on the road. Narcoleptic people who have trouble focusing on driving.
* **Target purchaser** Target group with special attention to families of unsafe drivers.
* **Customer service** Prefers easy to service products with comfort and convenience as a selling point.
* **Marketing & Sales division** Looks for unique selling points around safety and comfort when driving.
* **Retailers** Prefer products that can withstand a wide range of storage conditions including hot car temperatures, long battery life, fits in with the design of a car interior.


## Use Cases

### User Story #1: Noah

Noah is a 40-year-old man who drives long nights as a CDL Truck Driver. The drives stretch long hours and often far into the night. He has to keep going though, to meet his job's deadlines. His drowsy driver device senses whenever Noah drifts off and alerts him to stay awake on the road. It allows him to remain safe during long drives and deliver his loads.  

Noah thinks some designs of drowsy devices look silly, but the one he uses matches the style of his interior so when it's being stored it blends right in. It's compact for him to store safely when not in use and comfortable for him to wear for hours at a time. He enjoys knowing he has another safety step while he's driving his CDL truck.  

### User Story #2: Alexis

Alexis is a 21-year-old student at NAU. She is a full time student with a full time job and struggles to fit everything in her daily schedule. Alexis spends hours at the library studying or finishing homework before she has to clock in for her shift. With so much to do, Alexis uses a drowsy driver device to keep her focused on her work. It registers her heart rate slowing and sends a vibrational shock to her device, waking her up.

The device is traditionally marketed at drivers, but Alexis found it can be used in any setting to keep her focused. The device allows her to spend a little more time studying than she would otherwise get, and is sleek enough that no one in public questions her.  


## Aspects

The product design will be based on the wearable structure of a common portable neck fan, with functionality focused on driver safety, comfort, alert reliability, and customizable wake-up feedback. The P1 - P10 is the “code” used to indicate the priority of each requirement, from low to high.

1. **Hardware / Product Design**
   * 1.1 The product shall be ergonomic and comfortable to wear long term, especially for truckers and delivery drivers who drive for 10+ hours daily. (P10)
   * 1.2 Slim, breathable padded cushions near the neck allow for a non-intrusive design that conforms to the shape of the user’s neck, allowing for maximum comfortability and mitigating long-term irritation. (P10)
   * 1.3 The product shall incorporate a plastic chassis to allow for strength, durability, and rigidity, while keeping the internal sensors and electrical components safe. (P9)
   * 1.4 The product shall be symmetrical in design, making sure to balance the exterior shape and overall weight across both the left and right sides of the user’s neck. (P8)
   * 1.5 The exterior of the product shall be easy to clean, ensuring to not trap biological oils and sweat generated from the user. (P10)
   * 1.6 The product should have an ergonomic and straight-forward placement of buttons and interactive elements that can be easily accessible to a wide variety of users, even with limited hand mobility. (P9)
   * 1.7 The product should never obstruct head mobility typically required for driving, such as looking over the shoulder before making left/right turns. (P10)
  
2. **Software / Functionality**
      * 2.1 The product shall incorporate one or more optical proximity sensors to detect the user wearing it. (P10)
      * 2.2 Embedded motion sensors and visual sensors shall detect head movement and eye visibility. (P10)
      * 2.3 Embedded vibration motors shall agitate the user with haptic feedback, prompting the user to wake up and enter a state of being alert. (P10)
      * 2.4 Embedded LED warning lights shall alert the user with visual feedback, being non intrusive of road visibility but be positioned to prompt the user to look up at the road rather than pointing their head down in a drowsy state. (P10)
      * 2.5 The device shall incorporate enough sensors and emitters to clearly detect the user’s state of consciousness and alertness, even in a night-time setting with dim lighting. (P10)
      * 2.6 A large battery capacity shall ensure reliable and consistent life before needing the recharge. Additionally, the device can be operational while remaining plugged in for driving sessions that may exceed several hours. (P10)
      * 2.7 The universally available and widely-known USB C cable shall be used for charging the device’s internal battery and for continuous-power mode. (P7)
      * 2.8 The device shall enter a sleep/standby mode when not in use, preserving battery life. (P10)

3. **Interactivity / User Experience**
      * 3.1 The device shall include interactive elements, such as buttons, that are easily reachable and discernable from other buttons. This ensures that the user can operate the device’s power and settings with feel, rather than relying on seeing the buttons. (P8)
      * 3.2 The calibration should start up quickly after the device detects the user is wearing it. (P10)
      * 3.3 When the device has entered alert mode from detecting drowsiness, the driver can silence or acknowledge the alert with a quick button press, allowing the device to know that the user/driver is now in full consciousness. The device will then re-enter standby. (P10)
      * 3.4 The device should balance enough rigidity and flexibility to be easily taken on and off, to charge the device, and to store it when not in use. (P9)
      * 3.5 No complicated app shall be used in conjunction with the device, allowing simple operation without burdening the user with an app installation and confusing setup. (P5)
      * 3.6 A clear, legible instruction manual/guide shall be provided in the consumer package. (P8)
      * 3.7 The user experience shall be simple enough that the user can have the device activated before driving, without needing technical knowledge or a software app. (P8)
      * 3.8 The product shall be designed so as to prevent accidental use in any way, shape, or form. This may include false alarms, false power-offs, and more. (P10)
  
4. **Customization**
      * 4.1 The product shall flex slightly in design, allowing it to fit over a wide variety of general head shapes, and to rest over the neck and shoulders. (P8)
      * 4.2 The product shall feature adjustable vibration intensity, accommodating users who wake easily or users who sleep heavier. (P9)
      * 4.3 Different padding sizes can modularize the product to make it suitable for a much wider variety of neck types, ensuring all kinds of users can comfortably wear the product. (P7)
      * 4.4 Vibration intensity, LED alert intensity, and other kinds of sensational irritants (such as sound) shall be adjustable by the user, ensuring that the product isn’t painful (to the sensitive users), too distracting, or unusable (to the insensitive users). (P10)
      * 4.5 The exterior design layout shall feature enough smooth faces (surfaces) to allow for sticker placement or other user-defined decorations. (P1)
      * 4.6 The product shall come in a variety of different colors, accommodating users who have an enjoyment for vibrant colors and those who prefer minimal colors. (P1)

5. **Manufacturing**
      * 5.1 The prototype can be printed using readily-available FDM printing, balancing strength and low-volume manufacturing speeds. (P7)
      * 5.2 Breathable padded-mesh fabric for neck comfort. (P10)
      * 5.3 The battery shall be rechargeable with USB C, and may be user-replaceable once battery life/performance degrades over its expected lifespan. (P6)
      * 5.4 Off-the-shelf sensors and components initially reduce cost during prototyping, before future models can incorporate more advanced circuit boards. (P4)
      * 5.5 Quality control shall test vibration, battery, sensor accuracy, buttons, and reliable charging. (P6)
      * 5.6 The product shall be designed to consist of the minimum possible amount of parts, reducing redundancy and helping user-repairability. (P7)
  
6. **Safety**
      * 6.1 The product shall feature a safe water resistance, ensuring light spills won’t damage the electronics nor pose a risk to the user. (P10)
      * 6.2 The battery shall be outsourced from a reliable company that specializes in building safe batteries that are safe for wearable products. (P10)
      * 6.3 Exposed electronics, such as the USB C port, shall be located at the back and away from the face to ensure that drink spills or drool won’t enter through the port and cause probable damage to the device and pose a user safety risk. (P10)
      * 6.4 The internals of the product shall be built in a way to cradle the battery in a padded material, ensuring that accidental drops won’t pose a risk to the battery in terms of short circuits, chemical leaks, or dangerous thermal runaways (overheating and fires). (P10)
      * 6.5 The product must pass drop tests, ensuring that drops won’t compromise structural integrity, proving that the product is durable enough for daily use. (P10)


## Requirement Criteria Specifications

The device will need to conform to several specifications that will be mentioned. These are both technical and subjective requirements. 
1. **The product needs to be effective at keeping you awake.**
      * We need to test or verify in some way that the led’s, buzzer, and vibration motors which are operated by the sensors actually are effective at keeping drivers awake.
2. **Battery and power specifications**
      * We need the battery to last 8 hours minimum and the power output needs to hold 5 volts steady. We can simulate load on the battery along with stress test the power output regulator in order to make sure those are up to specification
3. **Physical size**
      * We will make sure that the final design is within the specifications of 11x5x4 inches and doesn’t exceed 5 pounds. We can do this by going a few inches under the size requirement in order to avoid dealing with tolerances going above the limit along with choosing materials and components that are ergonomic and relatively lightweight
4. **Safety**
      * This one can be hard to determine but I think the best we can do without actually testing it is to make sure that if the product were to be destroyed the electrical would not create a shock hazard or start a fire.
      * On top of that I think it should also be important to consider how dangerous the product could be in the event of an accident especially since it is around your neck. We need to design the product in such a way that during an impact the product itself doesn’t injure customers.

## Open Questions

* Are we able to make this product cheaper than our competitors without sacrificing effectiveness?
* Can we for sure state that the sensors will work under all conditions to accurately read drowsiness traits?
* What ways can this product fail and if it does fail how can we design it in such a way that it fails safely.
* How can we design the product in such a way that it lasts the longest without failing under normal usage conditions?
