 Phase shift oscillators are the [oscillators](https://electronicscoach.com/oscillator.html) that generate a stable sinusoidal signal at the output. Basically, the circuit has, an amplifier unit like transistor or op-amp along with a feedback network comprising of resistors and capacitors. Thus, is also known as **RC phase shift oscillator**.

The RC network is present in the feedback path is connected in ladder fashion thus also known as ladder RC phase shift oscillator. We know for an RC circuit; the output voltage leads the input for a sinusoidal waveform.

However, the phase angle by which the output leads the input relies on the values of R and C component.

We know to have **sustained oscillations**,

1. The loop gain of the oscillator must be equal to 1.
2. And the phase shift introduced by the circuit must be equal to 0 or 360⁰.

The amplifier circuit generates a phase shift of 180⁰. So, in order to achieve sustained oscillations, in RC phase shift oscillator, the feedback path must also provide a phase shift of 180⁰. Thus the achieved overall phase shift can be either 0 or 360⁰.

Also, loop gain equal to 1 can be achieved by tuning the gain of the amplifier and feedback circuit.

Let us first understand how the phase shift is being generated by the oscillator.

### RC Feedback Network

The figure below represents an RC phase shift feedback network, having a resistor and capacitor:
![hase shift oscillation single RC network](https://electronicscoach.com/wp-content/uploads/2019/06/phase-shift-oscillation-single-RC-network.jpg)

As we have already discussed that output leads the input in this case, thus, is also known as a phase lead circuit.

From the above circuit, we can say that the transfer function of the circuit is given as

![phase shift oscillator - eq1](https://electronicscoach.com/wp-content/uploads/2019/06/phase-shift-oscillator-eq1.jpg)

We know, **XC = 1 / ωC**

![phase shift oscillator - eq2](https://electronicscoach.com/wp-content/uploads/2019/06/phase-shift-oscillator-eq2.jpg)

So, the phase shift will be given as

![phase shift oscillator - eq3](https://electronicscoach.com/wp-content/uploads/2019/06/phase-shift-oscillator-eq3.jpg)

Thus by observing the above expression, we can clearly say that the phase shift depends on the value of R and C.

So, for a very small value of XC, φ will be equal to 0⁰. But when R is very small or 0 then it will cause XC/R to get equal to infinity, thus in this case φ will be 90⁰.

Hence from the above discussion, it is clear that the feedback circuit provides a phase shift between 0 to 90⁰.

But as we have already discussed that we require to have a feedback network that can provide us with a phase shift of 180⁰ in the phase shift oscillator. Thus the value of R in the circuit must be kept as low as possible, more specifically 0.

Suppose we have formed cascade connection of two RC stages, where each stage is providing a phase shift of 90⁰. Thus combinely we can have a phase shift of 180⁰. But in that case, if the value of R is 0, then the gain of the circuit will also be 0.

So, practically, one cannot have a phase shift of 180⁰ only by using 2 stages of phase shift oscillator. Thus to achieve a phase shift of 180⁰, despite using 2 RC stages we use 3 RC stages where each stage separately provides a phase shift of 60⁰.

The figure below represents the feedback network having 3 RC stages:

![3 stage RC phase shift oscillator](https://electronicscoach.com/wp-content/uploads/2019/06/3-stage-RC-phase-shift-oscillator.jpg)

As we have already discussed that to have the overall phase shift of 360⁰ around the loop, the feedback circuit must provide a phase shift of 180⁰. And in case of 3 RC stages, each stage must provide a phase shift of 60⁰.

It is to be noted here that the values of resistance and capacitance must be the same for each stage. So that each section of the feedback circuit produces a desired phase shift for a particular frequency.


### Construction

The phase-shift oscillator circuit consists of a single transistor amplifier section and a RC phase-shift network. The phase shift network in this circuit, consists of three RC sections. At the resonant frequency fo, the phase shift in each RC section is 60o so that the total phase shift produced by RC network is 180o.

The following circuit diagram shows the arrangement of an RC phase-shift oscillator.

![Arrangement RC](https://www.tutorialspoint.com/sinusoidal_oscillators/images/arrangement_rc.jpg)

The frequency of oscillations is given by



Where

R1=R2=R3=R

C1=C2=C3=C

### Operation

The circuit when switched ON oscillates at the resonant frequency fo. The output Eo of the amplifier is fed back to RC feedback network. This network produces a phase shift of 180o and a voltage Ei appears at its output. This voltage is applied to the transistor amplifier.

The feedback applied will be

m=Ei/Eo

The feedback is in correct phase, whereas the transistor amplifier, which is in CE configuration, produces a 180 phase shift. The phase shift produced by network and the transistor add to form a phase shift around the entire loop which is 360.




### Advantages

The advantages of RC phase shift oscillator are as follows −

- It does not require transformers or inductors.
- It can be used to produce very low frequencies.
- The circuit provides good frequency stability.

### Disadvantages

The disadvantages of RC phase shift oscillator are as follows −

- Starting the oscillations is difficult as the feedback is small.
- The output produced is small.