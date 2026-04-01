## Motion Detector, Rock & Roll Light Show, and Volume Meter

##  Introduction

This lab session focused on designing and testing three analog electronic systems using breadboards:

* Motion Detector
* Rock and Roll Light Show
* Volume Meter

The objective was to understand how sensors, amplifiers, and signal conditioning circuits can be used to detect 
environmental changes and produce meaningful outputs such as light indicators.

##  Components Used

* Breadboard
* Resistors (various values)
* Capacitors (electrolytic and ceramic)
* Potentiometer
* Operational Amplifier (Op-Amp IC)
* LEDs (Red, Blue)
* Microphone sensor
* Light Dependent Resistor (LDR)
* Transistors
* Power supply (9V)

##  Motion Detector
To detect motion or changes in light intensity using an LDR and trigger an LED output.
The LDR changes its resistance based on light intensity. When motion occurs, it alters the light falling on the sensor, 
causing a voltage change.
This voltage is fed into a comparator (Op-Amp), which switches the output HIGH or LOW depending on a reference threshold set using a potentiometer.
* LDR + resistor form a voltage divider.
* Output goes into Op-Amp comparator.
* Potentiometer sets sensitivity.
* When threshold exceeded → LED turns ON.
* Use shielding to minimize ambient interference.

##  Rock and Roll Light Show
To create a dynamic LED light pattern based on oscillating signals.
This circuit uses an oscillator (RC or Op-Amp based) to generate periodic signals. These signals drive LEDs to blink alternately, creating a visual light show.
* Capacitor charges and discharges periodically.
* Op-Amp or transistor switches states.
* LEDs alternate based on signal output.


##  Volume Meter
To visualize sound intensity using LEDs.
A microphone converts sound waves into electrical signals. These signals are amplified and compared against thresholds to light up LEDs proportionally to volume.
* Microphone captures sound.
* Amplifier boosts signal.
* Comparator stages trigger LEDs.
* Higher sound → more LEDs ON.

## Conclusion
All three circuits were successfully implemented on breadboards. The systems demonstrated fundamental analog electronics concepts such as:

* Signal sensing
* Amplification
* Threshold detection
* Oscillation

Each circuit had practical limitations such as noise sensitivity and calibration challenges, which are common in analog designs.
The lab provided hands-on experience in building real-world analog systems. It highlighted the importance of:
* Proper component selection
* Noise handling
* Calibration and tuning
