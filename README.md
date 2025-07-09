# Fire-Ex Robot

In places like homes and industries, there’s always a risk of sudden fire accidents. If no one is around to respond quickly, it can lead to serious damage.
We wanted to build something that could act immediately in such situations — without human help.

So, we designed an **autonomous robot** using **Arduino** that can detect fire using an **IR flame sensor**, figure out the direction of the flame, and move towards it.
Once it's close enough, it turns on a **mini water pump** to spray water and put out the fire.

Here’s how we built it
Required Components are: 
1. Arduino UNO
2. Fire sensor or Flame sensor (3 Nos)
3. Servo Motor (SG90)
4. L293D motor Driver module
5. Mini DC Submersible Pump
6. Small Breadboard
7. Robot chassis with motors (2) and wheels(2) (any type)
8. A small can
9. Connecting wires


The fire sensor detects flames and sends signals to the Arduino, which processes the input and triggers necessary actions. Once fire is detected, the Arduino activates the water pump, drawing water from the container and spraying it onto the fire to extinguish it. 

Simultaneously, the robot moves towards the fire using DC motors controlled by the L293D motor driver. A servo motor helps adjust the nozzle position for accurate water spraying. The entire system operates with a dedicated power supply, ensuring uninterrupted functionality. 

