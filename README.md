# now_playing
OBS Script to display now playing


OBS Fourms Project page: https://obsproject.com/forum/resources/now-playing.1160/

Original Project: https://obsproject.com/forum/resources/now-playing.783/

## How to use
**Notice: This script need Windows Vista+(dwm.exe)**
1. Install Python 3.6
2. Install Pywin32 (`python -m pip install pywin32 -U`)
3. Load the script
4. Create a GDI+ Text Source
5. Open script settings, set "Text Source"
6. Enjoy!

## Tips:
1. Only check the using player
2. Edit text source's transform settings
3. Don't set "Check frequency" too fast or too slow
4. Insure "Enabled" is checked
5. If the script raise errors, please send script log

## StreamElement SoundRequest Integration:
1. Download the chrome extension: https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld
2. Insert the custom script from ./script.js in the extension
3. Keep the Tab active while listening to the Sound Request; 