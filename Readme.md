# Fiber Optics Calculator

## Overview
This C++ program provides a set of calculations related to **fiber optics**, including numerical aperture, refractive index, acceptance angle, attenuation coefficient, and more. It is a **menu-driven program** that allows users to input fiber parameters and obtain key optical properties.

## Features
- **Numerical Aperture (NA):** Calculates the light-gathering ability of the fiber.
- **Relative Refractive Index (RRI):** Computes the relative and percentage refractive index difference.
- **Acceptance Angle (AA):** Determines the maximum angle at which light can enter the fiber.
- **V Number & Modes (VM):** Calculates the **V number** and determines if the fiber is **single-mode** or **multi-mode**.
- **Attenuation Coefficient (ACa):** Computes power loss per km in **dB/km**.
- **Power Calculations:** Determines **output power (ACpo)** and **required input power (ACpi)**.
- **Fiber Length Calculation (ACl):** Computes fiber length based on power loss and attenuation.
- **Graded Index Fiber NA (GRIN):** Computes **numerical aperture** variation in graded-index fibers.
- **Critical Radius (CR):** Computes the **critical core radius** based on **operating wavelength**.

## Requirements
- C++ Compiler (G++/MinGW for Windows, g++ for Linux/macOS)
- Basic understanding of optical fiber concepts

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/FiberOpticsCalculator.git
   cd FiberOpticsCalculator
   ```
2. Compile the program using g++:
   ```bash
   g++ fiberoptics.cpp -o fiberoptics -lm
   ```
3. Run the executable:
   ```bash
   ./fiberoptics
   ```

## Usage
1. Run the program.
2. Choose an option from the menu.
3. Input the required values.
4. Get the calculated result.

## Example Output
```
1: For Numerical Aperture
2: For Relative Refractive Index
3: For Acceptance Angle
...
Enter choice: 1
Enter value of refractive index of core: 1.5
Enter value of refractive index of cladding: 1.4
The numerical aperture of the given fiber is: 0.538
```

## Error Handling
- Ensures **n1 > n2** (necessary condition for total internal reflection).
- Uses **exception handling** to validate user inputs.
- Prevents division by zero and negative values.

## License
This project is licensed under the MIT License.

## Author
- Harsh Singh  
  [GitHub Profile](https://github.com/IndiHarsh)

