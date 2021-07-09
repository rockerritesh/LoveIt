---
title: "Amplifier"
date: 2021-07-08T13:42:04+05:45
draft: true
---

## class A
***
![classA](https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp21.gif "CLASS A")
The most commonly used type of power amplifier configuration is the Class A Amplifier. The Class A amplifier is the simplest form of power amplifier that uses a single switching transistor in the standard common emitter circuit configuration as seen previously to produce an inverted output. The transistor is always biased “ON” so that it conducts during one complete cycle of the input signal waveform producing minimum distortion and maximum amplitude of the output signal.

This means then that the Class A Amplifier configuration is the ideal operating mode, because there can be no crossover or switch-off distortion to the output waveform even during the negative half of the cycle. Class A power amplifier output stages may use a single power transistor or pairs of transistors connected together to share the high load current. Consider the Class A amplifier circuit below.

## class B
![classB](https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp25.gif "CLASS B")
![](https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp46.gif "waveform")
To improve the full power efficiency of the previous Class A amplifier by reducing the wasted power in the form of heat, it is possible to design the power amplifier circuit with two transistors in its output stage producing what is commonly termed as a Class B Amplifier also known as a push-pull amplifier configuration.

Push-pull amplifiers use two “complementary” or matching transistors, one being an NPN-type and the other being a PNP-type with both power transistors receiving the same input signal together that is equal in magnitude, but in opposite phase to each other. This results in one transistor only amplifying one half or 180o of the input waveform cycle while the other transistor amplifies the other half or remaining 180o of the input waveform cycle with the resulting “two-halves” being put back together again at the output terminal.

Then the conduction angle for this type of amplifier circuit is only 180o or 50% of the input signal. This pushing and pulling effect of the alternating half cycles by the transistors gives this type of circuit its amusing “push-pull” name, but are more generally known as the Class B Amplifier.

## class AB
![classAB](https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp47.gif "CLASS AB")
The Class AB Amplifier circuit is a compromise between the Class A and the Class B configurations. This very small diode biasing voltage causes both transistors to slightly conduct even when no input signal is present. An input signal waveform will cause the transistors to operate as normal in their active region thereby eliminating any crossover distortion present in pure Class B amplifier designs.

A small collector current will flow when there is no input signal but it is much less than that for the Class A amplifier configuration. This means then that the transistor will be “ON” for more than half a cycle of the waveform but much less than a full cycle giving a conduction angle of between 180o to 360o or 50% to 100% of the input signal depending upon the amount of additional biasing used. The amount of diode biasing voltage present at the base terminal of the transistor can be increased in multiples by adding additional diodes in series.

Class B amplifiers are greatly preferred over Class A designs for high-power applications such as audio power amplifiers and PA systems. Like the class-A amplifier circuit, one way to greatly boost the current gain ( Ai ) of a Class B push-pull amplifier is to use Darlington transistors pairs instead of single transistors in its output circuitry.

### crossover distortion
Crossover Distortion produces a zero voltage “flat spot” or “deadband” on the output wave shape as it crosses over from one half of the waveform to the other. The reason for this is that the transition period when the transistors are switching over from one to the other, does not stop or start exactly at the zero crossover point thus causing a small delay between the first transistor turning “OFF” and the second transistor turning “ON”. This delay results in both transistors being switched “OFF” at the same instant in time producing an output wave shape as shown below.
![crosses distortion](https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp26.gif "crossover distortion")
![crosses distortion]https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp48.gif "crossover distortion wave form")

This can be remove by
<ol>
<li>Pre-biasing the Output

The problem of Crossover Distortion can be reduced considerably by applying a slight forward base bias voltage (same idea as seen in the Transistor tutorial) to the bases of the two transistors via the center-tap of the input transformer, thus the transistors are no longer biased at the zero cut-off point but instead are “Pre-biased” at a level determined by this new biasing voltage.
![crosses distortion](https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp47.gif "crossover distortion pre-biasing")
</li>
<li> OR BY CLASS AB

![crosses distortion](https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/amplifier-amp49.gif "crossover distortion class AB")
</li>
