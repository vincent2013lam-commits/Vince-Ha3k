Starbie is an interactive electronic pet. It features a microcontroller, buttons, an Arduino code, and a custom design. The project consists with a Kicad schematic design, hosting all of the components, and a pcb design, where we construct and place all of the components. The code is in Aduino and in C++, featuring all of the starbie's responses and overall behavior.

Starbie Image:
<img width="872" height="573" alt="image" src="https://github.com/user-attachments/assets/d6b8d80c-ad6b-4121-bb13-8bb72a910376" />

(I may not add images)


First things, to make a Starbie, we need the following components:
- 0.96-inch OLED Display: Shows data from the Starbie Program
 
<img width="540" height="483" alt="image" src="https://github.com/user-attachments/assets/601d6195-d016-42bc-a4c3-164688f27f81" />

- XIAO ESP32 C3: Runs the Arduino code

<img width="390" height="337" alt="image" src="https://github.com/user-attachments/assets/c156e5ba-ae19-45bb-b655-731533e8124c" />

- DHT11: Measures the air temperature and humidity

<img width="355" height="428" alt="image" src="https://github.com/user-attachments/assets/12b0fa27-5523-4bbb-b6f8-d8775217582c" />

- MPU6050: Detects movement

<img width="1500" height="1500" alt="image" src="https://github.com/user-attachments/assets/56e67418-a4c5-4688-8e71-6642c724f969" />

- MX Switches: Allows pressing
  
<img width="495" height="456" alt="image" src="https://github.com/user-attachments/assets/69ae2f3f-991f-4054-8e81-2c5b85e76f25" />

- Keycaps: Allows pressing
  
<img width="605" height="487" alt="image" src="https://github.com/user-attachments/assets/69cfe818-7123-4e8f-bfcd-4fbac3b14433" />

- 10k Resistor: Controls electrical current
  
<img width="497" height="489" alt="image" src="https://github.com/user-attachments/assets/bef48649-1cd4-44f7-897b-cfa14ab37d8f" />

- PCB: The entire system the Starbie operates on

Bill of Materials Table:

<img width="622" height="334" alt="image" src="https://github.com/user-attachments/assets/b903c75f-696c-47e7-aa46-2fce06d2db37" />

Making the 5TARBIE process:
1. Sketch the needed components on the schematic editior
2. Transfer the schematic to the pcb editor
3. Wire every needed connection and design the base of your star
4. Use the Design Rules Checker to catch any mistakes










