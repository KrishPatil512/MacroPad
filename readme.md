MacroKeyboard Project

A simple custom macro keyboard built to trigger shortcuts, automate tasks, and speed up everyday workflows.



This project is a compact macro keyboard using a microcontroller (like ESP32) and programmable buttons to send custom key inputs to a computer. It can be used for productivity, gaming, or creative workflows.

 Features
Custom programmable keys
Supports keyboard shortcuts/macros
Compact and portable design
Easy to modify and expand
Can be used with different layouts


 Hardware Used
ESP32 / microcontroller
Mechanical switches / buttons
PCB 
OLED .96 in screen
Optional: enclosure (3D printed or case)
 How It Works

Each button is mapped to a specific function. When pressed, the microcontroller sends a signal to the computer (via USB) that acts like a keyboard input.

Example:

Button 1 → Copy (Ctrl + C)
Button 2 → Paste (Ctrl + V)
Button 3 → Open app
 Setup
Clone the repository
Upload code to the microcontroller
Connect via USB
Customize key mappings in code
 Project Structure
/code → firmware and logic
/pcb → PCB design files
/cad → enclosure / case design
/bom → bill of materials
 Future Improvements
Rotary encoder support
OLED display
Wireless (Bluetooth) control
Custom software interface


![alt text](<Screenshot 2026-05-03 184403-1.png>) ![alt text](<Screenshot 2026-05-01 181248-1.png>)