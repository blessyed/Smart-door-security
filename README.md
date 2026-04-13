# Smart Door Security System

## Objective

To simulate a smart security door system using STM32 that detects visitor presence and allows controlled door access.

## Hardware Used

* STM32 Nucleo Board
* Ultrasonic Sensor
* Servo Motor
* Buzzer
* External Button

## Components and Purpose

* **Ultrasonic Sensor** → detects visitor presence near the door
* **Servo Motor** → simulates door lock and unlock mechanism
* **Buzzer** → gives visitor alert sound
* **External Button** → manual approval for door opening

## Working Principle

* Ultrasonic sensor continuously monitors distance near the door area.
* When a visitor comes close, buzzer generates alert sound.
* Door remains locked until manual approval is given.
* Pressing the external button unlocks the door by rotating the servo motor.
* Releasing the button locks the door again.

## Example System Behavior

* Visitor detected → buzzer alert
* Button pressed → door opens
* Button released → door closes

## Real-Life Application

This simulates smart home and office entry systems where visitor detection and controlled access are handled automatically.

## Development Platform

* STM32CubeIDE
* STM32 HAL Library

