# Line Follower Robot

## Project Information
*Course:* IC 152: Makerspace Laboratory  
*Project:* Line Follower Robot (2023-24)  

## Introduction
A *Line Follower Robot* is an automated vehicle that follows a visual black line or path on a surface. The path can be a black line on a white surface or a white line on a black surface. This robot is controlled using *infrared (IR) sensors* and an *Arduino Uno*.

### Why Line Follower Robot?
- Uses *rechargeable Li-ion batteries*.
- Easily programmable through *Arduino code*.
- Efficient and cost-effective.
- Can be modified for different applications.

## Basic Working Principle
- *IR sensors* detect black and white surfaces based on reflection and absorption of IR light.
- *Arduino Uno* processes the input from IR sensors and controls the motors accordingly.
- *L298N motor driver* helps in driving the motors based on sensor input.

## Components Used
- *Arduino Uno*
- *Jumper Wires*
- *Car Chassis*
- *L298N Motor Driver Module*
- *IR Sensor Module*
- *Rechargeable Li-ion Battery*
- *On-Off Switch*
- *3D Printed Wheels*
- *Connecting Wires*
- *Soldering Iron & Solder Wire*
- *Hot Melt Glue Gun & Double-Sided Tape*
- *Ultrasonic Sensor*
- *Servo Motor*

## Circuit Diagram
(Refer to the circuit diagram in the documentation for details.)

## About the Components

### 1. Arduino Uno
An 8-bit *ATmega328P microcontroller* with 14 digital I/O pins, 6 analog inputs, USB connectivity, and a power barrel jack.

### 2. Infrared (IR) Sensors
- Emit IR light to detect surroundings.
- IR LED acts as an emitter, and an IR photodiode acts as a detector.

### 3. L298N Motor Driver
- Controls the speed and direction of *DC motors*.
- Operates with voltage up to *12V*.

### 4. BO Motors (Battery Operated Motors)
- Provide *good torque and RPM* at lower operating voltages.
- Used in *hobby projects*.

### 5. Lithium-Ion Battery
- Rechargeable battery used in *portable electronics* and *robotics*.

## Procedure

### 1. 3D Printing the Wheels
1. Design the wheels.
2. Export the design.
3. Prepare and print using a *3D printer*.
4. Mount and test the wheels.

### 2. Laser Printing the Chassis Board
- Design chassis using *Fusion 360* or similar software.
- Use *laser cutting* to create a precise chassis.
- Assemble and attach motors, sensors, and components.

### 3. Connections and Wiring
- *BO motors* connected to L298N motor driver.
- *IR sensors* connected to Arduino for line detection.
- Power supply managed through Li-ion battery.

### 4. Changing Speed
- *3 IR sensors* continuously track the black path.
- Left and right wheels adjust speed accordingly to follow the line.

### 5. Placement of Sensors
- Sensors should be *aligned* correctly for precise path detection.
- Adjust sensor height and distance for better performance.

### 6. Calibration and Testing
- Fine-tune *sensor sensitivity*.
- Test robot movement and *adjust the Arduino code* if needed.

## Key Learnings
- *Sensor Integration*: IR sensor calibration and integration.
- *Algorithm Development*: Implementing control theory in robotics.
- *Hardware Design*: Building and assembling physical components.
- *Problem Solving: Tackling challenges like **sharp turns and intersections*.
- *Programming Skills*: Enhancing logical and coding skills.
- *Testing and Iteration*: Improving performance through continuous debugging.

## Challenges Faced
### 1. Ambient Light Variations
- Different lighting conditions can affect IR sensor readings.

### 2. Line Width and Color
- Variations in line thickness or color contrast can impact detection.

### 3. Sharp Turns and Intersections
- The robot must adjust speed and direction to navigate corners properly.

### 4. Uneven Surfaces
- Bumpy or rough surfaces may cause instability.

### 5. Sensor Interference
- External infrared sources may interfere with sensor readings.

### 6. Calibration Drift
- Over time, sensor values may shift, requiring recalibration.

## Conclusion
The *Line Follower Robot* represents a remarkable intersection of *technology and practical applications. Its ability to **autonomously navigate* a predefined path using *infrared sensors* and sophisticated *algorithms* not only showcases the advancements in robotics but also opens doors to numerous real-world applications. 

From *industrial automation* to *educational projects, the Line Follower Robot serves as a **versatile tool* for enhancing efficiency and learning. As technology continues to evolve, we can anticipate *further refinements* in line follower robots, paving the way for increased *precision, adaptability, and integration* into various fields.

---

## Thank You! 🙌
