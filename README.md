# Talking-Tank-Plant #HackPackContest 
Hi, @August here!
For my submission I added a DF Mini Player to the Tank Plant. I wanted my final build to do this: When the LED matrix says a word (like DROWNING or SATISFIED) the DF Mini Player will play a file that speaks the same word out loud. How does this improve the Tank Plant? Well, what if you were in the other room and the Tank Plant says, on the LED matrix, THIRSTY? Only thing is, you were in the other room so you didn’t see it say that. 

The idea (for the DF Mini Player) came when I was doing my online class about C++, I was learning how to work with a DF Mini Player. After the lesson I knew that that was what I wanted to make my submission’s main attraction. 

The parts I needed were a mini breadboard, DF mini player, speaker, 1k ohm resistor and M-M wires. I didn’t just want to stick the breadboard to the Tank Plant, though (because then it’d be a pain getting off), so I tried a different way of getting it on without it falling off. I used 2 paper clips and 1 extra small rubber band, from a HackPack box, to make it so that the Mini breadboard would stay on. To get the paper clips on the back of the Tank Plant I just bent them until they were straight, stuck one end through the breadboard and made a hook on the other end. Finally, I used the hooked end to hook it on a corner of the Arduino Nano. I then needed to find a way to put the speaker on. I realized that I could use 2 bread-ties/twist-ties (they were used in the Card dealer) and stick them through the holes where the servo would go on the side. Then I just twisted them together on the inside of the Tank Plant.

I wanted to make my own MP3 audio files, only problem was…I didn’t know how to make one so after buying a microphone and watching a few YouTube videos I got my homemade MP3 files. I made 6 MP3 audio files, here they are in order with their file names next to them:

File 01 = Parched

File 02 = Thirsty

File 03 = Satisfied

File 04 = Drowning

File 05 = Isolate Me

File 06 = Scorched

(I've put the mp3 files on my github post for this hack)

The last thing to do then was modify the code to make this hack work. After 1 week of errors and me almost throwing my computer into the wall I got my first code with no errors. As you can expect it didn’t work, so after another week of staying up till 2:00am I was able to get it working! I decided to add a test line to see if the DF mini player was really working (line 264). 

Basically, if the Tank Plant has too much water the LED matrix will say DROWNING and every 15 seconds, while in that state, the DF Mini player will play file number 4. 

I had a lot of fun doing this hack and I learned a lot from it. I can also envision further modifications to this hack using mp3 audio files; for example, based on impact to bumpers (“Ouch!”) or distance from an object (“Out of my way!”).   It’s only limited by the imagination.  

Have a wonderful day. 	:) 

@August

