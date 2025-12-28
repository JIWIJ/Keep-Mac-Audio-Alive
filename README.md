# Prelimanary anticipating current version is fully adopted.

# KeepMacAudioAlive
Keep Mac audio alive to prevent delays or pops with some DACs.

The app can be installed two ways: Downloading it or building it yourself.

## How to download and run
1. Download the app from [releases](https://github.com/openmac/KeepMacAudioAlive/releases).
2. Open the app. Click Done on the first prompt. 
3. Allow the app to run via Privacy & Security settings in macOS System Settings. 
4. Start the app and select the desired device from the list under Device.  

   <img width="307" height="150" alt="Screenshot 2025-12-28 at 00 45 27" src="https://github.com/user-attachments/assets/e76f684e-fd69-4cde-adb1-99d527fee9ba" />

   The selected device is identified by having a checkmark to the left of its name.

   <img width="317" height="150" alt="Screenshot 2025-12-27 at 19 40 05" src="https://github.com/user-attachments/assets/75336816-cb2b-463e-b3de-4ef8ac3954e5" />   

5. Click Start to have it begin sending silence to the selected device. This disables the choice of device, which is enabled again by clicking Stop. 

   <img width="317" height="150" alt="Screenshot 2025-12-27 at 19 40 21" src="https://github.com/user-attachments/assets/9525d22f-b81d-48a9-9e26-bc9ac3f94752" />
  
   The selected device will be remembered on launch and the app will send silence right away the moment it is connected. It will always send silence on launch if the last selected device is available. If it is not, it will not send silence until another device is selected and Start is clicked or the last selected device is connected again.
   Note that when the logo is filled in, the app is sending silence and when it is empty, it is not. 

6. To launch at login, add this app to Login Items under Settings > General > Login Items & Extensions > Open at Login. As stated, when the last selected device is connected it will send silence right away.

## How to build
If you want to build it yourself:
1. Download the source code from this repository.
2. Download and install Xcode.
3. Open KeepMacAudioAlive.xcodeproj on Xcode.
4. Set your own signing profile.
5. Build or Run.
6. Follow 4. through 6. for the download version.

## Credits
This app and even its icon was origanally made using Gemini 3 Pro, so all credits to them, and use it at your own risk. The menubar UI was made by me using LosslessSwitcher as inspiration and source of some code, particularly in the AppDelegate. 
