# DS-Tech
The doorbell ringer is a device designed to notify residents of a house that someone is at the door. It produces sound when activated. 

![0](https://github.com/user-attachments/assets/73bf8ba4-e23a-4513-8dd0-4f36c874a75e)

![IMG_1716](https://github.com/user-attachments/assets/f89635f2-903a-411b-bfd2-2bc445e9c6d1)

Inputs: Push Button 1, Push Button 2 
Outputs: Doorbell Buzzer (Piezo) / LED

The buzzer produces a sound to notify people of a button press. 
The buzzer is connected to the output of the OR gate. 
When either input button is pressed, the OR gate outputs HIGH, turning the buzzer ON. 

Input HIGH: The buzzer receives power and emits sound. 
Input LOW: The buzzer remains off. 

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






