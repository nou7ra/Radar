 Radar System Using Arduino

 Project Description
This project implements a radar system using Arduino, an ultrasonic sensor (HC-SR04),
and a servo motor. The servo rotates the ultrasonic sensor to scan the surrounding area
and detect objects at different angles.

Components Used
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- Jumper Wires
- Breadboard

 How It Works
1. The servo motor rotates from 0° to 180°.
2. At each angle, the ultrasonic sensor sends an ultrasonic pulse.
3. The echo time is measured and converted into distance.
4. The distance and angle are displayed via the Serial Monitor.

 Connections
- Trig Pin → Digital Pin 2
- Echo Pin → Digital Pin 3
- Servo Signal → Digital Pin 9
- VCC → 5V
- GND → GND

 How to Run the Project
1. Open the `.ino` file using Arduino IDE.
2. Connect the components as shown above.
3. Upload the code to Arduino.
4. Open Serial Monitor at 9600 baud rate.

