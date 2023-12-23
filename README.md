# Smart Dustbin with Ultrasonic Sensor

## Hardware Required

1.

**Arduino Uno**

2.

**Ultrasonic Sensor HC-SR04**

3.

**SG-90 Micro Servo Motor**

4.

**Dustbin**

5.

**Full Kit**

## Software Required

1.

**Arduino IDE**

## Components Overview

### Arduino Uno

Arduino Uno is an open-source microcontroller board based on the ATmega328P processor. It is equipped with digital input/output pins, analog inputs, USB connectivity, and various other features. Arduino Uno is widely used for prototyping and creating electronic projects.

### Ultrasonic Sensor HC-SR04

HC-SR04 is an ultrasonic distance sensor utilizing SONAR principles to measure the distance of an object. It consists of a transmitter emitting ultrasound waves and a receiver detecting the echoed waves. The time taken for the waves to return determines the object's distance.

### SG90 Micro Servo Motor

SG90 is a lightweight, high-quality servo motor suitable for small robotics projects. It operates with most radio control systems and is commonly used in remote-controlled devices like helicopters, planes, cars, boats, and trucks.

## Working Concept

The Smart Dustbin aims to enhance waste disposal by incorporating a contactless approach. In response to the ongoing COVID-19 situation, this project utilizes an Ultrasonic Sensor HC-SR04 to detect objects in front of the dustbin. The sensor signals are processed by the Arduino Uno, which then commands the SG90 Micro Servo Motor to open the dustbin flap. The servo motor allows for a hands-free and efficient disposal mechanism. The flap remains open for a predefined duration (3 seconds in this case) before automatically closing.

## Circuit Diagram

![
Circuit Diagram
](https://raw.githubusercontent.com/itsbhupendrasingh/Smart-Dustbin-with-New-Blynk2.0_new-method/Master/smart_dustbin_ESP32.png)

The circuit consists of Arduino Uno, a power supply, and an ultrasonic sensor. Connect the Echo and Trig pins of the HC-SR04 sensor to Arduino Uno pins 5 and 6, respectively. The VCC pin goes to 5V on Arduino, and the grounds are connected. The signal pin of the Servo Motor connects to pin 7, with ground to ground and positive to 3.3V.

A 9V battery is connected to the Vin pin on Arduino Uno, and the grounds are interconnected.

## Program Code

The Arduino code for this project can be downloaded [
here
](link-to-your-code). Upload the code to Arduino Uno. Attach the Arduino and battery to the dustbin using double-sided tape.

For additional details and improvements, please refer to the [
code repository
](link-to-your-repo).

Feel free to modify the code to adjust the flap open duration or implement other enhancements.

Happy smart dustbin building!
