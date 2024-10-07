# Numeric Data Type in LabVIEW

This project demonstrates the use of numeric data types and event-driven programming in LabVIEW. It showcases multiple event cases with numeric operations based on user inputs.

## Overview

The program uses an event structure to handle different user interactions, with each event performing specific numeric calculations or actions based on the selected value. The key components include:

1. **Event Structure Handling Numeric Values**  
   The event structure listens for changes in multiple numeric value controls and responds accordingly.

2. **Event Cases**  
   The program contains several event cases, each corresponding to a value change of the numeric inputs (01, 05, 09, and stop). Each event performs different actions based on the numeric value or user input:
   
   - **Timeout Event:**
     - If no specific action is taken within a set time period, the timeout event triggers, and a numeric constant (`0`) is output to an indicator.

   - **"01" Value Change Event:**
     - When the numeric control labeled "01" changes, the program activates the corresponding LED indicator, signaling that the event has been processed.

   - **"05" Value Change Event:**
     - When the numeric control labeled "05" changes, a random number between `0` and `1` is generated and displayed.

   - **"09" Value Change Event:**
     - Similar to other value changes, the "09" event triggers a specific action, displaying a numeric value on an LED indicator.

   - **"stop" Value Change Event:**
     - When the "stop" control is triggered, the program executes an exit condition, stopping further operations.

## How It Works

- **Event Structure**:  
  The main part of the code is the event structure, which monitors various numeric controls and executes specific code when they change.
  
- **Numeric Operations**:  
  Depending on which value changes, different numeric operations are executed, such as generating random numbers, showing fixed numeric values, or controlling LED indicators.

## Usage

- Run the VI and interact with the numeric controls.
- Depending on the control value changed (01, 05, 09, or stop), observe the actions taken by the program, such as numeric values being displayed or LEDs being activated.

## Requirements

- LabVIEW software is required to open and run the VI.

## Code
![image](https://github.com/user-attachments/assets/0b148195-0b08-4c4f-b8b4-ce9cab0b5e43)
![image](https://github.com/user-attachments/assets/b5180f28-c4c2-4475-8014-0544869a949c)

![image](https://github.com/user-attachments/assets/5cb9fcc0-1bcb-4f1e-aee0-8761eaa9b2eb)

...

![image](https://github.com/user-attachments/assets/276239d8-a65b-48ae-9313-4d5cc248fde1)

![image](https://github.com/user-attachments/assets/b9affa81-0623-4e4a-b092-2a3e1d247dca)

## The appearance of the running program
![image](https://github.com/user-attachments/assets/a2d02c63-2c66-4549-8a4c-9f814e483314)

![image](https://github.com/user-attachments/assets/8b006423-be11-412b-b90d-3a48eca465de)

...

![image](https://github.com/user-attachments/assets/eb98ab42-f59b-4b83-bc9a-75e5552b7e9a)
