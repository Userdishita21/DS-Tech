# DS-Tech
The doorbell ringer is a device designed to notify residents of a house that someone is at the door. It produces sound when activated. 

![0](https://github.com/user-attachments/assets/73bf8ba4-e23a-4513-8dd0-4f36c874a75e)

![IMG_1716](https://github.com/user-attachments/assets/f89635f2-903a-411b-bfd2-2bc445e9c6d1)

A description and explanation of all the components/parts of the doorbell circuit: 

Inputs: Push Button 1, Push Button 2 
Outputs: Doorbell Buzzer (Piezo) / LED

1) LED: It provides a visual indication showing that the circuit is active.
2) Resistor: It limits the current going to the LED to prevent damage.
3) Push Buttons (Switches): Used to trigger the doorbell when pressed. They work as input to activate the cicuit.
4) Quad 2-Input OR Gate: The OR gate lets the buzzer be triggered by the push buttons/switches. For instance: If there are two push buttons (one at the front door and one ate the back door), pushing either button will activate the buzzzer. Furthermore, the 74HC32 combines these signals, making sure the circuit responds to any input.
5) Buzzer/Piezo: Emits sound when the circuit is activated, acting as the actual doorbell ringer (notifying residents of the button press). It is connected to the output of the OR gate. When either input button is pressed, the OR gate outputs HIGH, turning the buzzer ON. 
6) Breadboard Power Module: Supplies power to the circuit thrugh the USB connection. It distributes power to the breadboard rails.
7) Connecting Wires: Form electrical connections between components.

Input HIGH: The buzzer receives power and emits sound. 
Input LOW: The buzzer remains off. 

Each component/part of the circuit is there for a reason. These parts were carefully chosen in order to receive the best possible outcome, and build an efficient doorbell ringer. 

<img width="982" alt="Screenshot 2025-01-20 at 10 53 30 AM" src="https://github.com/user-attachments/assets/8460c466-04ca-4ad7-a0d2-1b00cd5566a9" />

<img width="669" alt="Screenshot 2025-01-20 at 10 56 04 AM" src="https://github.com/user-attachments/assets/8d10818d-c4b5-4d5d-ac5b-85be2c5ab3b4" />

Karnaugh Map / Boolean Logic Simplification:

Scenario: 
Two buttons: A and B
Output: Y (activates the ringer)
Logic Equation: 
Y = A + B 
Where: 
“+” represents the OR operation. 
Simplification: 
Since A + B is already in its simplest form (OR logic), no further simplification is needed. 

Website Made By: Dishita Sareen




