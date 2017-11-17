# SoundControl

We have created software that can be used by anyone to create new musical instruments using their choice of movements, sensed with a variety of off-the-shelf sensing devices (including webcam, Leap Motion, microbit, GameTrak). These instruments can be used to play and manipulate musical material, which can be either new material recorded by users or taken from third-party sample libraries.

To be able to use the full functionality of this code compile the code to a .app file inside the Sound_Control folder. Then put the whole Sound_Control folder in your /Applications/ folder. This app was built for OSX.

The goal of the Sound Control project is to collaborate with youth with special needs and disabilities in designing, developing and building bespoke digital musical instruments personalised for their unique needs.

The Sound Control project is supported by a Paul Hamlyn Foundation “Widening Access and Participation in the Arts” grant. The project is led by the Northamptonshire Music and Performing Arts Trust.


## Externals & 3rd Party Software Used

### CBMicroBit
https://github.com/Louismac/CBMicroBit

### RapidMax.mxo
http://gitlab.doc.gold.ac.uk/spark041/RapidMax_release

### Changelist.mxo
http://www.jasch.ch/dl/default.htm

### Shell.mxo
https://cycling74.com/forums/chess-for-max/replies/1#reply-596a3e15d5b2a4159a6c7d04 

http://expr-i0.net/shell_170717.zip

### Leapmotion.mxo
https://www.julesfrancoise.com/leapmotion/
https://forge.ircam.fr/p/leapmotion/

## Known Bugs

There is currently no way to change the the audio I/O for the app. To change this you will need to change the audio settings in max and rebuild.

The colour tracker does not work with more than 2 input devices.