# DIRTA-Water-Tester

This repository contains the design and implementation details of an accurate pH meter device specifically engineered for pool water measurement. The device combines specialized hardware components with algorithms to provide precise pH readings.

## 📐 **Objective**

Develop an accurate pH meter device for pool water by integrating specialized hardware components and algorithms.

## 🛠 **Functional Components**

- **Analog pH Sensor**: 
  - Function: Measures the pH value of the solution.
  - Mechanism: Produces a voltage based on ion reactions, indicating the pH level.

- **pH Conversion Module**: 
  - Function: Regulates voltage and calibrates sensor output.
  - Features: Ensures supply voltage remains between 3.3V to 5.5V and contains a variable resistor for calibration.

- **STM32 Nucleoboard**: 
  - Role: Acts as the central microcontroller.
  - Function: Processes the analog voltage reading, converting it into a pH value, and communicates the result to the LCD.

- **16x2 LCD Display**: 
  - Function: Displays the calculated pH value.

## 📦 **Device Design**

- **External**:
  - Material: Sturdy ABS plastic.
  - Dimensions: 158 x 90 x 60mm.
  - Features: Houses the Nucleoboard, LCD, and conversion module. BNC connector and CN2 USB ports accessible externally.

- **Internal**:
  - Layout: Optimized placement of components to facilitate easy wiring and circuitry.

## 🧠 **Algorithm Employed**

- **Insertion Sort**: 
  - Use Case: Sorts the voltage values fetched by the pH sensor. 
  - Benefit: Calculating the median of sorted values and determining the mean provides a more accurate pH reading by excluding outliers.

## 🧪 **Scientific Principle**

The device's pH measurement is grounded on ion reactions at the probe, which yield a voltage that correlates with the pH value. This voltage is then processed and exhibited.

## ⚙ **Technical Specifications**

- Accuracy: Measures pH within a margin of +/- 0.1 at 25°C.
- Speed: Displays results within 2 minutes from the time of measurement.
- Durability: Probe longevity surpasses 0.5 years.
- Efficiency: Circuit energy consumption is capped at 30W.
- Operational Range: The probe functions optimally between 5 to 60°C.

