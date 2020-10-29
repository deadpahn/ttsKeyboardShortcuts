# ttsKeyboardShortcuts

A collection of useful commands that allow text to speech functionality to a GNU/Linux desktop. They can be assigned to keyboard shortcuts.
# Dependancies
sudo apt-get install xsel espeak;
# Reads highlighted text
bash -c "xsel | espeak -s 220 -v en-us"
# Stops the currently read text
bash -c "pkill espeak"
