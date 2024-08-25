## PLC Logic: One Push On, One Push Off Using Positive Pulse

This repository contains a simple PLC logic project developed using Siemens SIMATIC Manager Step 7. The project demonstrates a basic control logic where a single push button alternates the state of an output (e.g., a light or motor) between ON and OFF with each press, utilizing a positive edge detection (positive pulse).

### Key Features
- **Push Button Control**: A single push button (input) is used to toggle the state of an output device.
- **Positive Edge Detection**: The logic uses a positive edge (rising edge) trigger to detect each push of the button.
- **Toggle Functionality**: On the first push, the output turns ON; on the next push, the output turns OFF, and this cycle continues with each subsequent push.

### Getting Started
1. **Requirements**:
   - Siemens SIMATIC Manager Step 7.
   - Siemens S7-300/S7-400 PLC hardware or PLCSIM for simulation.

2. **Installation**:
   - Clone the repository.
   - Open the project in SIMATIC Manager.
   - Download the program to the PLC or simulate using PLCSIM.

3. **Usage**:
   - Connect the push button to a digital input (e.g., I0.0) and the output device to a digital output (e.g., Q0.0).
   - Run the program and observe the toggling action with each button press.

### Project Structure
- **Main Program Block**: Contains the logic for positive edge detection and toggling.
- **Documentation**: Includes comments and documentation within the code for clarity and understanding.

### Contributing
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
