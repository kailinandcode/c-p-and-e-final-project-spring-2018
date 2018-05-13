

NB: You might find useful the [sample proposal](http://github.com/zamfi/ucb-jacobs-creative-programming-electronics-spring-2018/blob/master/hw/sample-proposal.md) useful in completing this assignment!

# Zoomba

Zoomba is a battery-packed powered robot that picks up letters from the floor and can shoot out confetti/positive cheer.

## Team

Sandy Chu, Kailin Li, Alvin Tan. 

## Summary
//Write a paragraph or two describing what you built for your final project and what was challenging. 

The final design of the Zoomba is a 6 x 8.5 inch 4 wheeled platform with a small box to store objects/mail/confetti and a red flag. The 
bottom of the platform houses four wheels controlled by input from the featherboard and motor controller, a custom 3d printed 'v-bottom' 
with a backpack strap to gather debris from the ground, and 2 servos with custom 3d printed arms to close the bottom and prevent debris from escaping the bottom. 

We intended on having our Zoomba use sensors to execute specific actions when certain conditions were met, such as closing off the servo 
arms when a light sensor on the bottom went below a pre-defined lower limit and using the Ultrasonic distance module to detect obstructions and instruct the wheels to reverse and look in other directions to decide its next path, but were unable to implement these features due to hardware failures that prevented us from troubleshooting these errors in time for the Jacobs Showcase. 

Our final iteration of the Zoomba relies on a set code that showcases a number of functions that it can perform proficiently. 

## Component Parts

HC-SR04 Ultrasonic Sensor Distance Module (5pcs) for Arduino UNO MEGA2560 Nano Robot XBee ZigBee by ElecRight

4 Pcs Arduino Plastic Tire Wheel with DC 3V 5V 6v Gear Motor For DIY Robot Smart Car Robot

Supporting Swivel Caster Wheel - 1.3" Diameter (scrapped from final design)

Light sensor and 2 LEDs (scrapped from final design)

3D Printed filament 'V-bottom' and 'servo tail'

Backpack straps

Wires, Motor Controller, Battery Packs/Portable Battery

1/8" plywood board 'face' and 'flag' 

1/4" plywood board w/ laser cutter adjustments

2 Breadboards

1 Battery Pack

3 Servo motors

1 Featherboard

Include what types of inputs/outputs/data it will use, and a block diagram showing how all those pieces are connected.

## Challenges

A significant challenge with our project was learning how to use new hardware and working around part failures and difficulties. Our 
design relied on a number of sensors and motors to create a system that would respond accordingly to various inputs from its 
environment. In order to produce a final, viable project, our group constantly learned to take the working parts of our project and 
pivot away from its weaknesses and highlight its strengths.  

The first significant hardware failure began with the light sensor that lost sensitivity and gave inaccurate readings to the serial 
monitor. Without the light sensor, our plan to use LEDs and "trash" objects to have the featherboard instruct the wheels and servo to 
behvave in a certain manner failed. 

The second significant failure occured in the Ultrasonic Sensor Distance Module our group purchased from 3rd party sellers. Initially, 
the distance sensor reported accurate readouts when it was directly connected to our laptop. However, when our group attempted to 
implement the distance reader with the other hardware, it consistently returned incorrect values even when connected with the original 
setup that gave correct distance values. The loss of the Ultrasonic Sensor caused our group to once again pivot and rely on coding and a 
pre-set environment to protect it from collision with other objects. 

Despite the many setbacks our group decided to stick with the basics of the original design and transform the prankster roomba into a 
mailbot, inspired by Amazon drones and Kiwibots. 

## Timeline

What did you do in each of the past five weeks?

- Week 1: Write Proposal, Brainstorm ideas on various "annoying" robots

- Week 2: Order Materials and initial planning/logistics

- Week 3: Assembly/Code, meetings on Designs/challenges

- Week 4: Assembly/Code, troubleshooting and pivoting

- Week 5: Present!

## Completed Work

Photos and videos of your completed final project!

## References and links

https://www.youtube.com/watch?v=XmYqvloiWg0

http://www.instructables.com/id/CleanBOT/

**Include a link to your final showcase one-pager here in PDF format.**

Tutorials, comments, videos, magazine articles - anything you found that helps you understand your project.
