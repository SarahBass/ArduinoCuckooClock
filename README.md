# ArduinoCuckooClock
A programming project using Arduino IDE , Arduino Uno, and Arduino Mega

Test Model built inside a handmade wooden clock, and final project built into a broken cuckoo clock antique that needs repair. 

The Arduino Cuckoo Test Clock will have the following features:
----------------------------------------------------------------------------------------------------------
  A LCD Display of temperature, date, and time
  A motor driven calendar and day clock wheel (attached to motor and something I carved from wood)
  A passive buzzer that plays a random 16 note song every hour with no repeat songs
  A bluetooth device that sends the data from the clock to an Android Phone to keep track of data
  A LED Matrix Advent calendar that displays a little animation for the holidays
  A string of LED lights for christmas that play with tune of christmas songs on passive buzzer
  A servo motor driven cuckoo bird that pops in and out of a hole once an hour
  Additional components (Temperature Sensor, A real time clock module, a clock mechanism with a pendulum from a kit)

The Final Model for the broken Cuckoo Clock will only run the preexisting features of the original clock:
----------------------------------------------------------------------------------------------------------
  A new motor for a wheel of spinning dancers
  A new clock, pendulum motor, and cuckoo bird device playing a random song 
  A Transceiver to send bluetooth data to Andriod Phone for random Cuckoo Songs played
  A string of LED lights that interact with song if drilling holes does not jeapordize the clock framework (As the old wood is brittle). 

Future project upgrades (If I can get anymore wires in there) include Ultrasonic sensor interacting with Cuckoo bird, so that when a hand is raised by the door, the bird pops out. Possibly a better speaker that could play bird sounds instead of a simple passive buzzer.

Goal: The cuckoo clock never repeats a song, and always generates a new tune upon the hour. It plays 16 notes out of the library of notes given by 
"pitches.h" and picks a random tempo from 1, 2, 4, 8, and 16 for each note. Using a seperate program on an app built for Android Phones, the bluetooth transmitter will record an array of the notes randomly selected and tempo, and then compare the notes using document distance functions to a repository
of pre-existing songs. It will display to the user which song their random song most closely matched (on notes alone) and give them an option to rate it.

User can keep the storage of dates and times of the songs played on the cuckoo clock, organize them in a list based on which ranked worst and best, and replay the songs. The user can also program the clock to go into multiple modes (can also be controlled through external remote). 

________________________________________________________________________________________________________________________________________________
Mode 1: Birthday Mode 
Instead of a random song played, the cuckoo clock plays the birthday song for 24 hours straight upon the hour, led lights light up, LED matrix shows cake and LCD screen flashes "Happy Birthday"

Mode 2: Holiday Mode:
The clock plays 12 holiday songs every 12 hours, and a tiny advent calendar LED matrix image, led christmas lights light up

Mode 3: Hannukah Mode:
The clock plays 6 hannukah songs at exactly 6PM to 12PM and the 9 led lights display from 6PM to 12PM, updating upon 6PM for 8 days. 
LED Lights:
> Day 1: ----o---o
> Day 2: ----o--oo
> Day 3: ----o-ooo
> Day 4: ----ooooo
> Day 5: ---oooooo
> Day 6: --ooooooo 
> Day 7: -oooooooo
> Day 8: ooooooooo

Mode 4: Halloween Mode
The clock plays 12 holiday songs every 12 hours, and a tiny LED matrix image shows spooky animations, led halloween lights light up

Mode 5: Saint Patricks Day Mode: 
The clock plays 12 Irish songs every 12 hours, and a tiny LED matrix image shows pot of gold animations, irish lights light up

Mode 6: USA Mode
The clock plays 12 USA songs every 12 hours, and a tiny LED matrix image shows USA animations, USA FLAG lights light up

Mode 7: German Octoberfest Mode:
The clock plays 12 German songs every 12 hours, and a tiny LED matrix image shows food animations, lights light up

Mode 8: Valentines Day Mode
The clock plays 12 love songs every 12 hours, and a tiny LED matrix image shows heart animations, lights light up

Mode 9: Cinco De Mayo Mode:
The clock plays 12 Cinco De Mayo songs every 12 hours, and a tiny LED matrix image shows food animations, lights light up

Mode O: Normal Random Mode Reset

(Future Clock revisions to include Chinese new year Mode, Black History Month Mode, Womens Apreciation Day Mode, and others upon getting an upgraded remote with more buttons. App on Phone must match remote settings.)

