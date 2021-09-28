# Movement detected workspace swithcer

Simple python script that switches your workspace/Desktop

# How it's done?
It uses openCV to detect movement through your webcam, and then pyautogui to press keyboard shortcut to switch your workspace, this mean you have to one workspace to right.

# How to set-up
Currently there is no simple way, you have to have installed Python and Pip.
1. Download [python](https://python.org)
2. Set-up python with pip so you can install some dependencies
3. Install pyautogui using this command:  `pip install pyautogui`
4. Position your webcam so when you start it doesn't just change workspace
5. Run the python script

**Note:** Once it detects movement it stops the program so you have to run it again if you want to use it
