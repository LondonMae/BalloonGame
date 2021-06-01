# BalloonGame
The balloon game is intended for virtual reality research at Rhodes College. See the menu below for more information.

- [Build Settings](#build-settings)
- [Pull Requests](#pull-requests)
- [Compiling to Oculus](#oculus)



### Build Settings
- launch in Unity version 2020.3.9f1
- Run on Android platform
- Texture Compression: ASTC

### Pull Requests
Before you can request the project code on your local device, you must first fork the project to your Github account. You can do this by clicking the fork button on the top right of the repository. 

Next, you will clone the project. Click on the green Clone button, and copy the link. Open your computer's terminal and type "git clone https://github.com/[USERNAME]/BalloonGame.git". You should now have the project on your local device. 

### Oculus
Plug in the Oculus device using the USBC cable, plugging one end into the Oculus and one end into the computer. Once dev settings are enabled and the Project is on your local device, go to file > Build and Run. You can now find the App in the Oculus under APPS > Unknown Sources > Com.RhodesCollege.BalloonGame. You can change the name under Edit > Player Settings > Player. 

### The Game
- Controls: simply move the controllers to pop the balloons - no button pressing necessary
- Balloons will fall from the SpawnPos in randomly sized groups every 3 seconds. The balloons vary slightly in size and drag (falling speed).
- The player is free to move and rotate as they would like
- The balloons will "pop" once they reach the ground or hit the players hand. The player misses a balloon if it pops on the ground rather than their hand. 

Balloon Game was coded by London Bielicke
For more information contact me at bielm-24@rhodes.edu
