# BanG Dream! Bot (2020)

## Description

This bot can autonomously play most of the easy and normal songs from "BanG Dream!".

Video of the bot playing &ndash; [https://youtu.be/dJgJXFNFZ8E](https://youtu.be/dJgJXFNFZ8E).

## Requirements

1. Windows PC.

2. Python 3.6+ ([OpenCV](https://pypi.org/project/opencv-python/), [PyAutoGui](https://pypi.org/project/PyAutoGUI/), [NumPy](https://pypi.org/project/numpy/), [PyWin32](https://pypi.org/project/pywin32/), [Keyboard](https://pypi.org/project/keyboard/)).

3. BlueStacks.

## Instructions

### Setup Game

1. Install "Bang Dream!" on BlueStacks.

2. Change your game settings.
   - **Live Settings**
     - Note Speed &ndash; 4.2
     - Note Size &ndash; 160%
     - Song Adjustement &ndash; Any
     - Long Note Transparency &ndash; 100%
     - Dual Tap Line &ndash; No
     - Off-Beat Coloring &ndash; No
     - Mirror &ndash; No
     - Lane Effects &ndash; No
   - **Effect & Sound Settings**
     - Control Mode &ndash; Low
     - Fever Effect &ndash; Low
     - Memver Cut-in &ndash; Low
     - Skill Window &ndash; No
     - Skill Effect Text &ndash; No
     - Playback Quality &ndash; Low
     - Live Mode Quality &ndash; Low
     - Live Mode Brightness &ndash; 60%
     - Music Video Live Member &ndash; No
     - Live Volume &ndash; Any
   - **Live Theme Settings**
     - Lane Design &ndash; Fifth
     - Tap Effects &ndash; Fifth
     - Event Live Background &ndash; No
     - Note &ndash; Type 3
     - SE &ndash; Any
   - **System & Push Settings**
     - System Volume &ndash; Any
     - Fix Screen &ndash; No
     - Shortage Check &ndash; No
     - Check Battery Level &ndash; No
     - Ad Check &ndash; Any
     
3. Import [controls](controls.cfg) into BlueStacks.
   - Open the game on BlueStacks.
   - Open "Controls Editor" (Ctrl + Shift + A).
   - Click on "Import".
   - Select [controls](controls.cfg).
   
### Execute Bot

1. Download this project.

2. Open "Bang Dream!" on BlueStacks. 

3. Go to the home screen (where we see the characters talking).

4.  Run [```src/main.py```](src/main.py) with Python (make sure BlueStacks is in the foreground).

5. Follow the displayed instructions.

6. Do not touch anything when the bot is playing.
