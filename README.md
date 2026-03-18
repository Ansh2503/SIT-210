# SIT-210 # Task 1.1P – Lights ON System 
## Description This project shows a simple lighting system using Arduino. 
A push button is used to control an LED light. When the button is pressed, the LED turns ON and stays ON for 30 seconds. When the button is not pressed, the LED stays OFF.  This project demonstrates basic Arduino programming such as using input and output pins, reading button input, and controlling an LED.  
## Components Used 
- Arduino board
- LED
- Push button
- Resistor
- Jumper wires
- Breadboard
- ## Code Explanation
-  ### Variable Declaration Two variables are created in the code: - `LED` is the pin number where the LED is connected (pin 12).
-   `BUTTON` is the pin number where the push button is connected (pin 4).  ### Setup Function
-    - The `setup()` function runs once when the Arduino starts.
- `pinMode(LED, OUTPUT)` sets the LED pin as an output so the Arduino can control the light.
     - - `pinMode(BUTTON, INPUT)` sets the button pin as an input so the Arduino can read when the button is pressed.  ### Loop Function The `loop()` function runs again and again. - `digitalRead(BUTTON)` checks if the button is pressed. - If the button is pressed, the LED turns ON using `digitalWrite(LED, HIGH)`. - The LED stays ON for 30 seconds using `delay(30000)`. - If the button is not pressed, the LED turns OFF using `digitalWrite(LED, LOW)`.  ## Outcome The system shows how a push button can be used to turn a light ON or OFF using Arduino. 
