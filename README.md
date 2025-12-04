DIY Smart Street Light User Manual
This user manual will guide you through the setup, operation, and maintenance of your smart street lights.
Table of Contents:
1.	Overview
2.	Components Included
3.	Setup Instructions
4.	Operating Instructions
5.	Maintenance
6.	Troubleshooting
7.	Safety Precautions

Overview:
The goal of the do-it-yourself Smart Street Light project is to give metropolitan areas automatic, energy-efficient lighting. The street lights are controlled by Arduino-based technology, which offers functions including vehicle detection, maintenance tracking, and automatic nighttime activation.

Components Included:
1.	Arduino Uno
2.	IR sensor (x3)
3.	Breadboard
4.	Male-to-Male AND Male-to-Female wires
5.	LED lights (x3)
6.	LDR module
7.	Servo motor
8.	Actuator



Setup Instructions:

The steps are mentioned below:

Mounting the Street Light Assembly:
 Select an appropriate location for the street light assembly, ensuring it receives maximum sunlight (or any light that will increase the threshold level of the LDR below 500) exposure. Using the supplied mounting hardware, securely fasten the street light assembly to a pole or structure. Make sure it is stable and capable of withstanding various weather conditions.
Connect the Components:
 Follow the wiring diagram included with the project to correctly assemble the components.
 Connect the DC motor and actuator to the Arduino Uno.
 Properly attach the IR sensor to the Arduino Uno.
 Use the provided wires and connectors to ensure secure and reliable connections.
Upload the Code to the Arduino Uno:
 Connect the Arduino Uno to the computer using a USB cable.
 Launch the Arduino Integrated Development Environment (IDE) on the computer.
 Open the pre-written code for the smart street light project.
 Click the "Upload" button in the Arduino IDE to transfer the code to the Arduino Uno.
Installing the IR Sensor:
 Mount the IR sensor securely beneath the street light assembly, ensuring it faces downward.
 Position the sensor so it has an unobstructed view to detect vehicles passing below.

Operating Instructions:

Once set up, the smart street lights will operate automatically:
Daytime Configuration: 
During daylight hours, the street lights will remain at ground level for maintenance.
Nighttime Activation: 
As darkness falls, the lights will raise to an elevated position for optimal illumination.
Vehicle Detection: 
The lights will intensify to an appropriate level when a vehicle is detected underneath.


Maintenance:
Maintaining smart streetlights is crucial for ensuring their optimal performance and longevity. Here's how to keep them in top condition:

Wiring and Connection Inspection:
Regularly inspect the wiring and connections for any signs of wear, damage, or corrosion.
Tighten any loose connections and replace damaged wires or connectors as needed.
Cleaning the IR Sensor Lens:
Clean the lens of the IR sensor regularly to ensure accurate vehicle detection.
Use a soft cloth or cotton swab lightly dampened with water or a mild cleaning solution to wipe the lens.


Lubrication of Moving Parts:
Lubricate the moving parts of the mechanism, including the Servo motor to prevent friction and ensure smooth operation.
Use a suitable lubricant as recommended by the manufacturer.

Troubleshooting:
1.	The biggest challenge was the decision to run 3 servo motors as Arduino is incapable of smoothly running 3 SG90 servo motors simultaneously.
2.	Different porting errors in different devices while running the IDE.
3.	Constant earthing shocks from the LDR module and the sensors sometimes.
4.	A faulty motor was given by the vendor.  
5.	Heating of Arduino for not using an external battery or power source, and for running it directly from the CPU.
Safety Precautions:
1.	Avoid touching the components with a wet hand
2.	Carefully connect the wires to the processors and the sensors so that they don't get damaged.
3.	Wear a protective glove or something else to avoid getting a shock from earthing issues.
4.	Fit the motors perfectly to the sheet so that it does not jump off while rotating.


