# Micro-Watch

## Description
This is a code that is written in Python and uses the MicroBit module to make it compatible with Microbits. 
The code essentially gives the MicroBit several features that would be commonly seen on a smart watch, hence the name "Micro-Watch". 

## MicroBit Simulator
To see the code actually working for yourself, go to [MicroBit's Python Editor](https://python.microbit.org/v/3). 
Copy and paste the code from the main file into the editor and it will show you a MicroBit running the code. However, not all features will be avaiable on the site since most of feature require the sensors built in the an actual Microbit. 
If you do have a MicroBit, go to website linked above and click send to Microbit. 

## Features 
Notes: 
- To switch to the next mode, press the B button. To go back to the previous mode, press the A button.
- Whenever it is mentioned that a pin must be pressed or held, you must hold the ground pin and "press" the mentioned pin.

There are a total of 10 different modes for the Micro-Watch. 
1. Time Mode (Clock Picture)
- You can set the time in the 12 hour time using this mode (it will unfortunately not count the minutes or hours like an actual clock would) 
- Press the MicroBit Logo to see what time is currently set (12 am by default)
- Press Pin 0 to change the hours using the A and B button
- Press Pin 1 to change the tens digit of the minutes using the A and B button
- Press Pin 2 to chage the ones digit of the minutes using the A and B button
- To get out any of the sub-modes, press the logo and it will allow you to switch modes 

2. Flashlight Mode (Flashlight Picture) 
- You can use a flashlight in this mode
- Hold Pin 1 to "use" the flashlight (it will basically just show very bright pixels on the MicroBit)

3. Step Counter Mode (Legs Walking Picture)
- You can track your steps in this count
- Every time the MicroBit is shaked, the Accelerometer in the MicroBit will detect it and count it as one step
- Press Pin 1 to see how much step you have 
- Press Pin 2 to see how much calories you have burned (it will go into decimals if not enough steps are taken) 

4. Music Mode (Music Note Picture)
- You can hear various default sounds that are built into the MicroBit 
- Press Pin 0 to hear the Ringtone sound
- Press Pin 1 to hear the Jump Up sound 
- Press Pin 2 to hear the Power Up sound 

5. Temperature Mode (Themometer Picture)
- You can see the current temperature using the built in Temperature Sensor
- Press Pin 1 to see the temperature in Celsius
- Press Pin 2 to see the temperatuer in Fahrenheit 

6. Fun Mode (Location Symbol Picture)
- Orignially, this was supposed to be a mode to help you find your MicroBit if you ever lost it
- However, we were not able to successfully implement a proper way of doing this
- Press Pin 1 to hear a funny sound

7. Noise Level Mode (Microphone Picture)
- You can detect the current noise level in your close area
- Hold Pin 1 to check the noise level in real time (the small square means its quiet and the large square means its loud) 

8. Dice Mode (Dice Showing One Picture) 
- You can roll a six-sided dice
- Press Pin 1 to roll the dice

9. Emotion Mode (Smiley Face Picture) 
- You can see different emotions on the MicroBit
- Press Pin 1 to see a happy face
- Press Pin 2 to see a sad face 
- Press the logo to see a surprised face

10. Direction Mode (Dot Picture)
- You can tilt the MicroBit towards a direction and it will change the picture on the screen
- You can tilt left, right, up and down to see the corresponding arrow. 
