# DIRTA-Water-Tester

Objective: Develop an accurate pH meter device for pool water using a combination of specialized hardware components and algorithms.

Functional Components:

Analog pH Sensor: Measures pH value of the solution. It produces a voltage based on ion reactions which indicates the pH of the solution.
pH Conversion Module: Acts as a voltage regulator ensuring the supply voltage remains between 3.3V to 5.5V. It also contains a variable resistor for calibrating the pH sensor output voltage.
STM32 Nucleoboard: Central microcontroller board responsible for processing the analog voltage reading and converting it into a pH value. It then communicates the pH value to the LCD for display.
16x2 LCD Display: Displays the calculated pH value.
Device Design:

External: A sturdy ABS plastic enclosure of dimensions 158 x 90 x 60mm housing the Nucleoboard, LCD, and conversion module.
Internal: Proper placement of components for easy wiring and circuit implementation. BNC connector and CN2 USB ports accessible from outside for user interaction.
Algorithm Used:

Insertion Sort: Helps in sorting a list of voltage values read by the pH sensor. Taking the median of sorted values and computing the mean ensures a more accurate pH reading by eliminating outliers.
Scientific Principle:
The pH measurement relies on ion reactions at the probe, producing a voltage representative of the pH value. The system then processes and displays this value.

Technical Requirements:

Accurate pH measurement within +/- 0.1 at 25°C.
Display results within 2 min of measurement.
Probe longevity of over 0.5 years.
Circuit energy consumption under 30W.
Probe functionality between 5 to 60°C.

![dirta1](https://user-images.githubusercontent.com/132171741/235389864-235d6d29-f96e-4708-a6c8-fe0be561f29a.jpg)
