# nom_mid
Sends MIDI to local DAW via routing through broswer. Uses Web MIDI API (https://webaudio.github.io/web-midi-api/). This API requires Google Chrome. 


Dec-6-2016 

To Do:
-Add select device to send to (I believe this is causing multiple signal issue when sending to Ableton via IAC driver)
-Add browser-browser link
-Test in Windows

Tested:  -Works using Virtual Input port on Massive
         -"Multiple signal" issue in Ableton with Apples virtual IAC driver, but recieves data
