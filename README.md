# Auto-Detection Security (Lock)

**Author(s)**: *Raymond Okyere-Forson & Elyor Tukhtasinov*

**Google Document**: *https://docs.google.com/document/d/1EXmQ7teX7KDZrPH5cdPVMI5438ql7kau7XEo_zoTTfA/edit?usp=sharing*

---
## Purpose
*Did you forget to lock? LockPro v1 has your back!*

Elyor's roommate frequently forgets to lock the door. Unfortunately, the dorm room doors in the Deep Green Residence Hall do not autolock themselves after left unlocked for an unreasonable amount of time (more than 5 minutes). The problem is that somebody else can access the dorm room and potentially steal Elyor's and his roommate's belongings. LockPro v1 will auto-lock the door after it has been left unlocked for 5 minutes. Also, the sound detection security will simulate a door-locking system that can be voice (or sound) activated. At the prototype stage, the lock will be simulated with a red LED when the door is locked and with a green LED when the door is unlocked. The voice/sound lock/unlock functionality can help in case Elyor or his roommate lock themselves out of the room by leaving their IDs inside.

## Initial Design Plan
*To build LockPro v1, we will be using different hardware components along with the master code that will run the entire operation.*

- Arduino UNO
- Breadboard
- Relay
- Magnetic Lock (MagLock)
- Switch
- Button (Would be potentially experimented on with a different function)
- Door Sensor (Might be used in place of switch)
- Power Supply (12V)
- Power Probes
- Connecting wires (Jumper Wires)
- Jumper Cables
________________________________________________________________________________________________________________________________________

- Initializing constant and global variables, if any.
- Assigning pins to the appropriate components.
- Turning on or off MagLock based on door sensor.

*Please see attached file: LockPro_Start_Code.ino to view full pseudocode.*


**Breadboard**:

![This is the breadboard view of project](images/bb.png)

**Schematic**:

![This is the schematic view of project](images/schem.png)

## Files
*The list of all files currently being used in this project.*

- Knock_example.ino: an example of code that uses piezo sensor to sense knocking (vibration)
- README.md: master file where we document everything about our project
- example-README.md: example of the master file with instructions that we have to follow in filling out our README.md
- images (folder): is a folder to store images to be inserted in README.md
- LockPro_Start_Code.ino: our master file for the code that currently contains the pseudocode
- MagLock Code_1.ino: Currently the best version of working code we have so far based on progress
- maglock_pro.ino: Trying to setup an auto-lock function of the system
- maglock_pro_v1.ino: Displaying progress of trying to make the code work
- maglock_pro_updated: Makes button unlock maglock, else it's always locked

## Summary
*You'll complete this part at the end of the project.*

Provide a brief summary description of the design and implementation,
including how much your initial design plan evolved, the final result
you achieved and the amount of time you spent as a programmer in
accomplishing these results, including any challenges overcome and
innovations that were not specifically required by the assignment.
This section should be no more than three paragraphs.

## Instructions
Explain how to use your product. 
This section should THOROUGHLY describe its usage (i.e., more than just "Push start").

## Errors and Constraints
*You'll complete this part at the end of the project.*

Every program has bugs. Use this section to create a bullet list of
all known errors and deficiencies that remain in your product. 
Also, list any constraints that must exist for your product to work 
(e.g., Only works in low light situations).

## Reflection
*You'll complete this part at the end of the project.*

Write 2 - 4 paragraphs on your reactions to the final project. 
Your reflection should be thoughtful and reflective. 
It is NOT a report about WHAT you did. 
Instead, it's a look back at what you learned by doing this project.
It should be critical of shortcomings (yours, as well as the instructors/assignments) 
as well as celebratory of what was achieved.

## References
- Sensor (Elyor: to determine whether Red or Green LED (lock imitation) is on; an analog pin should serve the purpose) Citation: https://startingelectronics.org/articles/arduino/measuring-voltage-with-arduino/
- Piezoelectric Sensor (Learned about it in the Arduino: examples>sensors>knock, googled and found this: https://youtu.be/1SNC3ib10_4)
- General research & useful sources: https://www.instructables.com/id/How-to-Make-Voice-Controlled-LEDs-Using-Arduino/ & https://play.google.com/store/apps/details?id=appinventor.ai_nitinpandit_00.Arduino_bluetooth_voice_controller&hl=en_IN

*Start this section at the beginning of the project, and update it throughout.*

Throughout this project, you'll be used outside resources.
Reference ALL ideas or code which are not your own, and describe and
how you integrated the ideas or code into your program. This includes
online sources, people who have helped you, and any other resources that
are not solely your own contribution. Lastly, include ALL resources you
looked at, not just the ones you ended up using directly.

## Final Self-Evaluations
*You'll complete this part at the end of the project. 
Assign points to each team member in each category, based on their contribution to the team. 
The sum of all member's points in each category cannot exceed 10. 
For example, for Coding, Partner 1 could get 7 points, and Partner 2 gets 3 points. 
You can't give both people 6 points each though, as the sum exceeds 10.

### Ideation, Brainstorming, Design:

*Partner 1 (replace this with your name): 0-10*

*Partner 2 (replace this with your name): 0-10*

### Code creation: 

*Partner 1 (replace this with your name): 0-10*

*Partner 2 (replace this with your name): 0-10*

### Documentation creation:

*Partner 1 (replace this with your name): 0-10*

*Partner 2 (replace this with your name): 0-10*

### Teamwork & Participation:

*Partner 1 (replace this with your name): 0-10*

*Partner 2 (replace this with your name): 0-10*


---
**A Note from Scott to You**

While I expect this project to have issues, one
thing to keep in mind is HAVE FUN with it! Create a product that
expresses your personal interests. Break up the writing so it’s not so burdensome.
We will have a live demo sessions at the end of the project to celebrate your accomplishments.

