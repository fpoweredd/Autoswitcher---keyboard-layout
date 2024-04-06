I use a keyboard with the Latin alphabet instead of the English layout, but I prefer the interface language of my operating system to be English.

For some reason, Windows does not allow me to hide or remove the keyboard layout I do not use if I want Windows to be in English, but the non-flexible settings do not allow me to do so.

### py kbswitcher.py

This script in an infinite loop helps me to skip the unnecessary layout.

### win autorun

Open PS

whoami - YOUR_USER_NAME

schtasks /create /tn "kbswitcher" /tr "python PATH_TO_FILE_PY" /sc onlogon /ru YOUR_USER_NAME
