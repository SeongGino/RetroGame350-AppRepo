The following is a direct copy-paste from the provided updater package. Any Engrish is unmodified from the original, and only minor formatting has been done for GH clarity. Thank you for your understanding.
---
***As for the release for RG350 handheld HDMI upgrade patch test version Beta RG350-HDMI-BETA1.1-UPDATE-2020-05-10(20200510)***

***This version is RG350 public beta version. BUG is not ruled out. I hope that players can feedback to the RG350 player interaction group during the beta. We will further modify and improve the HDMI function so that a better gaming experience will be brought to everyone!***

***Thank you for your support and cooperation!***

***Before upgrading, please make sure your machine is the official system! ! !***

***For the irreversible consequences caused by the unofficial system, please bear your own responsibility! ! !***

The following [RG350-HDMI-BETA1.1-UPDATE-2020-05-10 important operation guidelines], please read and operate carefully, you can participate in the HDMI upgrade patch public beta activity!

[RG350 Handheld HDMI Test Important Operation Guidelines]:
1. HDMI upgrade
Put RG350-HDMI-BETA1.1-UPDATE-2020-05-10.opk in the Apps folder of the external TF card
After booting, you can see an OS Update program in the application group. A enters the select update and executes it. Press start and follow the prompts.
Finally, press the start button on the main interface, turn on the HDMI switch, plug in the HDMI cable, and press any key to display it on the TV. It is the same operation to pull the HDMI cable.

2. Xmame simulator
Enter and click the game to adjust Sound Freq to 44100

3. fba simulator
After upgrading HMDI, you need to set the default value of the FBA simulator.
 and open the FBA simulator and press start to enter the Default ROM settings. At this time, there are two options in the list: default run game settings and Delete all saved ROM configs. Enter the default run game settings first, set the audio sample rate to 44100hz, and return to the previous layer and click Delete all saved ROM configs, and then go to the list of games, just click on a game to view it, hertz defaults to 44100, which means success.

4. fc simulator
Enter any game, press L1, enter Settings, enter Video setup and adjust Video scaling to fc fast, then go back to the previous layer, enter Sound Setup, set Sound rate to 44100, go back to the previous layer, save all settings as default, press Save config as default so other games also have this setting, then return to the game screen, if the screen is not full, press the power button to add A to fill the screen,

5. gba simulator
Open the display settings, and replace the image scaling with Full, Linear.

6. gngeo simulator
Select OPTION, press A to change the Sample Rate to 44100, then press Save conf for very game to save as the settings for all games

7. mame4all simulator
 (this simulator has poor compatibility, so it is recommended to use FBA simulator)
You can enter any game and set the sound option to 44.


Common problem solving

    • 1.Connect to the HDMI and the screen goes black
At this time, just press any button then can connect

    • 2. The Fc simulator screen is not tiled
Press Power + A key can usually be tiled, if can’t, you can press L1, enter Settings, enter Video setup and adjust Video scaling to fc fast

    • 3. The mame simulator sound with high voice pitch
Set Hertz to 44 before entering the game

    • 4. The game cannot be connected to HDMI in the emulator
As long as you exit to the main interface, you can connect to HDMI.

    • 5. Black screen when connect HDMI in the emulator or in the game
You can select + power button to force to quit, exit to the main interface and then connect to HDMI again, it is best to connect HDMI to the main interface and enter the emulator.

    • 6. The ps simulator screen display is not accurate
Press the power key to enter the menu, then enter GPU settings, set the video scaling, switch between hardware mode or nearest mode to solve the screen problem.
Optional: Set Frame skip to 1, most games do not need to manually stretch the frame.
