# install-GSI-Trebledroid-to-Xiaomi-Redmi-K50-rubens
#Download a GSI rom
#Unlock bootloader of the phone
Install the MIUI china version: V13.0.13.0.SLNCNXM (Other versions will meet no in-call audio issue)
Download a GSI rom
Plug the phone to computer
Restart to fastboot mode (normal FASTBOOT mode)
On computer: fastboot reboot fastboot (to start the phone to FASTBOOTD mode)
On computer: fastboot flash system name.of.the.GSI.image
Wait the flashing process to be done, then run: fastboot reboot (to reboot)
If phone boots to recovery mode: select the 2nd option (by pressing the down volume button), press Power to select; on next screen select the 2nd option, press Power to select to agree to Reset user data.
Install magisk
Download and install the overlay module at this link: https://github.com/his0ka/GSI-overlay-RedmiK50-magisk
DONE.
