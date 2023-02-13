# Marquee Sign

For our first assignment, we will be working within some constraints. Making your first DIY circuit board involves learning quite a few new concepts and techniques, so we will be working within some design limitations to help you focus on what's important.

![image of lighted sign spelling "HAPPY BRITHDAY"](https://user-images.githubusercontent.com/25984901/213777840-c148e1cf-cd5b-4346-ad2e-9608f06034c3.png)

What is a marquee sign? These are signs that are filled with lights, where each letter is formed by a series of individual bulbs or LEDs.

## Project Description

We will be creating a group project, each of you making a PCB in the shape of a letter. Together, all your letters will spell a phrase. Your PCBs will have LEDs on them and a capacitive sensor, so that they can light-up and be interactive.

To make a letter PCB, you will need a few important things on it:

* **Microcontroller** (to run your code)
* **LEDs** (to create light)
* **Transistor** (to PWM all the LEDs)
* **Capacitive Sensor** (to make it interactive)
* **Power Connectors** (to turn it on)
* plus resistors, capacitors, and points to connect programming wires

https://homemadehardware.com/img/marquee-H-video.webm

In my PCB above, I am using a quarter for my capacitive sensor. You can pick and conductive thing (metal, conductive thread, etc), and attach it to your PCB. Please do not pick a sensor that is larger than your PCB!!!

Once our PCBs are ready, we will assemble them together to spell out our phrase. Below is a (bad) drawing of how they will be connected together.

![image of a circuit board diagram in shape of letter "H"](https://homemadehardware.com/img/marquee-drawing.jpg)


## Pick a Phrase

What will our sign say? That is up to you. Please go to [this document](https://docs.google.com/document/d/1C88aAiYlG1RbK7elHKDKEcYGM6VkHlNWGrHehz59ck8/edit?usp=sharing), and add an idea for a phrase. Together we will vote for the one of your ideas to be the class phrase.

For example, phrases chosen for past classes were:

* pw is int3ract
* It Worked Before
* Microcontrol Me!
* I Dislike Pigeon
* Error Compiling!
 
We will vote in-class on the final phrase, before you start designing your circuits in Eagle.

## Project Requirements

There are a few things that are required of your circuit for it to pass. These are that your circuit must:

* be completely designed and fabricated yourself
* be on a single-sided PCB, no bigger than 70mm x 70mm (can be smaller)
* use less-than-or-equal-to (<=) 25 LEDs
* use one capacitive sensor (can be anything conductive)
  * Install the [CapacitiveSensor Arduino Library](https://github.com/PaulStoffregen/CapacitiveSensor)
  * This libary allows you to turn any pin into a capactive sensor. All you need is a 1M or 10M Ohm resistor.
  * Helpful video explainer [here](https://www.youtube.com/watch?v=jco-uU5ZgEU&t=8s). Library useage and information and examples [here](https://www.pjrc.com/teensy/td_libs_CapacitiveSensor.html).
* have two power connectors, for both input and output
* use only SMD parts
* include one mounting hole (placed anywhere) that is 3.3mm in diameter
* Please test these on 5 volts power! 
