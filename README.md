# ME35 Final Project: Cake Maker #
Code for the frosting portion of the Cake Maker robot, the final project of the Intro to Robotics & Mechanics course in Tufts University's spring 2022 semester. For more information on the overall project and on the image processing development, please visit [the cake maker page on my portfolio](https://meganjenney.wixsite.com/portfolio/cake-maker).

## Frosting Overview ##
The frosting portion of this robot has two key components:
1. An image uploaded from an Airtable form is parsed into an array of line contour coordinates.
2. The coordinates inform the robot where to dispense frosting on a baked cake.

## Files ##
**main/frosting_board.py:** Defines the frosting board object, which uses two motor objects defined in frosting_motors and interprets coordinates from img_processing.

**main/frosting_main.py:** Controls the robot using the frosting_board object and img_processing functions.

**main/frosting_motors.py:** Defines the motor object used in the frosting_board.

**main/img_processing.py:** Image processing framework. Includes functions necessary for cake position verification and coordinate parsing.

**main/sims/sim.py:** Simulates the robot movement.
