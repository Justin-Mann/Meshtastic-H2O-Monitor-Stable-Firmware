# Meshtastic-H2O-Monitor-Stable-Firmware
Temp repo to host a stable meshtastic firmware build that supports the RAK12035 and RAK12500 when using a RAK4631 

# TEMPORARY
The plan is to eventually get this bad chicken into a main version of the Meshtastic firmware project.  I'm just putting this here to make it avaliable to folks and it will be removed once the code is merged with the main firmware code.

# Couple Thinks To Be Aware Of...
This is just built from a branch of the Meshtastic Open Source Project (amazing work by an awesome community and group of project moderators and coordinators if you are unaware) I did a lil, and stood on the shoulders of giants as I did.  All this is is a slight modification of the main project to support a very specific hardware stack and allow for the use of the RAK12035 Soil Moisture Sensor with the RAK4631.  All credit to the Meshtastic team for the help and support doing so.
I managed to use is back to back and it's grammatically correct so ... good on me. I broke it (English). :)

ChatGPT: The sentence "All this is is a slight modification of the main project to support a very specific hardware stack and allow for the use of the RAK12035 Soil Moisture Sensor with the RAK4631." is understandable, but it’s awkward and potentially confusing due to the repetition of "is is" — even though it's grammatically defensible.

I am proud.

Anyways...
Check out Meshtastic.. It's an open source mesh network monster (in a good way) and it's only getting stronger. Gonna just take a second to state there are other awesome up anbd comers in this area as well, but Meshtastic provides... so much more than encrypted communications; such as RAK module support as above and support for o so many devices. Good stuff.

# INSTRUCTIONS FOR USE
Simple... 

1> Download the .uf2 file from this repo to your computer;

2> Connect the RAK with the processor and modules mounted (baseboard w/ 4631 or 4630 in the EU, RAK12035, RAK12500) with a data capable usb;

3> Double tap the reset button on the RAK to put it into bootloader mode (This will bring up an explorer window on your computer, similar to plugging in a usb stick);

4> Drag and drop (copy) the .uf2 file into the RAK window;

5> let the transfer complete, the device will restart.. Glory achieved.

6> If you are unfamiliar with Meshtastic and it's use you can learn more from the Meshtastic Resources, or if you want specifics about how to enable or how I am using this firmware yiou can look at the instructible I posted for the build.

# THE FUTURE
When the main Meshtastic project supports this code.. this repo disappears. Instead of this you'll be able to use their online Device Flashing Utility (as it should be). 
