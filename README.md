# Design of a RF Power Amplifier using ADS
Project Summary
## Introduction:
This project, conducted by Sami Fahim and Jordan Chometton, focuses on the design and optimization of a Radio Frequency (RF) power amplifier using the Advanced Design System (ADS) software by Agilent Technologies. RF and microwave devices are crucial in modern telecommunications, and efficient design using CAD tools like ADS helps minimize manufacturing costs and lead times.

## Objective:
The primary goal is to model an RF amplifier using a bipolar NPN transistor (BJTM1 model). The process involves selecting, modeling, and parameterizing the transistor to evaluate its performance in RF applications.

## Key Stages of the Project:

### Transistor Operation Modes:

Active Mode: Used for amplification where the base-emitter junction is forward biased and the base-collector junction is reverse biased.
Saturation Zone: Both junctions are forward biased, acting as a closed switch.
Cut-off Zone: Both junctions are reverse biased, acting as an open switch.
Determination of Optimum Bias Point:

The maximum gain is achieved with a base current between 20 and 30 μA.
A polarization current of 50 μA under a voltage of 3V was chosen for versatile amplifier design.
Stability Analysis:

Initial simulations showed that the amplifier was not unconditionally stable.
A stabilizing coil (1nH inductance) was added, improving the Rollet factor (k = 1.041) and Δ = 0.498.
S-Parameters Study:

Initial reflection coefficients indicated the need for adaptation due to significant capacitive components.
Adaptation circuits (L-circuits) were designed to improve impedance matching and overall gain.
Adaptation and Optimization:

Optimization targets: S11 and S22 to be -20dB maximum, S21 to be 15dB minimum.
Post-adaptation, the amplifier remained unconditionally stable with improved S-parameters.
### Large Signal Study:

Compression point at 1dB was determined to be -12dBm.
## Two-Tone Study:

IIP3 (third order intercept point) was measured at -1.57dBm using two 100 kHz spaced tones.
## Conclusion:
The project provided practical experience in RF amplifier design using ADS software. It reinforced theoretical concepts and highlighted the importance of simulation and optimization in achieving optimal performance. The skills gained are valuable for future endeavors in the field of RF and microwave engineering.

For a detailed analysis and further insights, please refer to the complete project report.
