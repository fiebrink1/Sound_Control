![alt text](/logos/gif2.gif?raw=true "Title")

# Sound Control

We have created software that can be used by anyone to create new musical instruments using their choice of movements, sensed with a variety of off-the-shelf sensing devices (including webcam, Leap Motion, microbit, GameTrak). These instruments can be used to play and manipulate musical material, which can be either new material recorded by users or taken from third-party sample libraries.

The goal of the Sound Control project is to collaborate with youth with special needs and disabilities in designing, developing and building bespoke digital musical instruments personalised for their unique needs.

The Sound Control project is supported by a Paul Hamlyn Foundation “Widening Access and Participation in the Arts” grant. The project is led by the Northamptonshire Music and Performing Arts Trust.

## Externals & 3rd Party Software Used

### CBMicroBit
https://github.com/Louismac/CBMicroBit

(Update Microbit Info)

* In order to use the CBMicrobit.exe with Sound Control as sources instead of as a Standalone, CBMicrobit.exe must be at the directory /Library/Application Support/Sound_Control/CBMicroBit. The .pkg downloader puts it there for you.
* To use the Micro:Bit you have to load it with a .hex file. There are currently two different micro:bits in rotation:
    * New Micro:Bit: If you have a new microbit it probably has a combined accelerometer and magnetometer, in this case you should load the "CBMicroBit-New-Combined-Accelerometer-Compass.hex" onto your Micro:Bit.
    * Old Micro:Bit: If you have an old microbit it probably has a separated accelerometer and magnetometer, in this case you should load the "CBMicroBit-Old-Separated-Accelerometer-Compass.hex" onto your Micro:Bit.
    * Both can be found in the resources folder.

### RapidMax
* Mac
https://github.com/samparkewolfe/RapidMax
* Windows
https://github.com/samparkewolfe/RapidMax_win

### Shell.mxo
https://cycling74.com/forums/chess-for-max/replies/1#reply-596a3e15d5b2a4159a6c7d04 

http://expr-i0.net/shell_170717.zip

### Leapmotion
https://github.com/JulesFrancoise/leapmotion-for-max/releases

https://developer.leapmotion.com/get-started/

* In order to run the Leap Object in Max the Leap SDK must be installed as well.
* There is a link in Releases to the Leap SDKs
* If you are building on windows to build Sound Control from sources you need to download the leap motion object from releases and put a .dll file that is provided in your Max MSP directory.

### Colour Tracker (original)
https://cycling74.com/forums/colour-tracking-with-a-webcam-in-jitter/

## Win Vs Mac
Sound Control source has a build for windows or mac flag, this is what it changes.
(Insert flag instructions here)
* Which Gametrak encoding method is used
* Whether the microbit sensors show up in the umenu.

## Saving Functionality
* In order to include the saving functionality when building a standalone from sources read the info.txt file inside resources/Custom Saving Scripts.
* This process happens after building the standalone so one can not save instruments by just using the scripts.

## Known Bugs
(Update)

The app automatically sets it’s audio I/O to whatever the I/O settings of the Max.app are. If you want to change these you must close the Sound Control app, set the desired audio I/O settings in the Max.app and then reopen Sound Control. However you can then change the audio I/O settings for the Max.app and not change the Sound Control audio I/O settings after the Sound Control app has been opened.

![alt text](/logos/NMPAT_long.jpg?raw=true "Logo1")
![alt text](/logos/pfh.jpg?raw=true "Logo2")
![alt text](/logos/Youth_Music.jpg?raw=true "Logo3")

## Building
* Insert build instructions here

## Navigating patcher
(Insert info on Max menus, window no-grow etc.)

