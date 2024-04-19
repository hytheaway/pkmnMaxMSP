# pkmnMaxMSP
![pkmnMaxMSP](https://github.com/hytheaway/pkmnMaxMSP/assets/91982175/5c843f29-9c36-4fde-83ae-ae16d7f47145)

a maxmsp patch that breaks a gameboy screen up into four chunks, then spits out an auditory expression of the matrix data of each of those four chunks.
shockingly straightforward. check out a demo here: https://youtu.be/AFi1Px7UF9E

want to try it yourself?
1. open up the game of your choice in an emulator.
2. open obs and resize the canvas to fit the emulator's screen. start the obs virtual camera.
3. open the max patch and set the camera to obs virtual camera.
4. play the game and let your imagination run wild.

some notes:
- some emulators don't have control over what audio device they send to. for this, i used loopback.
- gameboy screens are 160x144. the max patch looks for 320x244, which can be set as the canvas (and therefore camera) resolution in obs.
- this is loud! always check your volumes!
