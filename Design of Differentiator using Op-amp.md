# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DIFFERENTIATOR

## AIM:
To design and test the performance of differentiator circuits using Op-amp.

## APPARATUS REQUIRED:
<img width="984" height="273" alt="image" src="https://github.com/user-attachments/assets/2bfcbf8e-9b24-441c-a0c5-b04e0b1bee8d" />

## THEORY:
## DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,

Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1. Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 μF, calculate the value of Rf.
2. Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.
The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM:
<img width="1437" height="1080" alt="image" src="https://github.com/user-attachments/assets/75a1735e-9589-496b-91cf-b8e82d14bbf1" />

## MODEL GRAPH:
<img width="778" height="1301" alt="image" src="https://github.com/user-attachments/assets/ef1dd7b5-7f22-44f1-ae1d-1a663236444b" />


## PROCEDURE:
### Differentiator:
1. Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4. The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
   
## DESIGN:
<img width="837" height="443" alt="image" src="https://github.com/user-attachments/assets/fee44ef4-8ae5-4b7a-938e-927c4492992e" />

## TABULATION:
<img width="1253" height="829" alt="image" src="https://github.com/user-attachments/assets/b8ae9a9f-b064-4d23-bb3e-ac0afa390728" />


## GRAPH:
<img width="1080" height="1329" alt="image" src="https://github.com/user-attachments/assets/aff742db-2bae-4c80-b48c-16fabd3570f0" />
<img width="1049" height="1347" alt="image" src="https://github.com/user-attachments/assets/9556bf69-e179-48d4-91da-b11e2a860687" />



## RESULT:
Thus the Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.

