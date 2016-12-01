# pebblePairToWT12
Wixel code to handle the initial pairing between the BlueGiga WT12 and a pebble watch
<br><br>
Modified version of a standard program wireless_serial.c.
This is much easier then the arduino method that uses the RN-41 for bluetooth.
<BR><BR>
Beware, when you bring up the serial term, you should see some text from the WT12, if it's unresponsive, power cycle the device and try again. <br>
Sometimes it takes a couple of tries.<br>
<br>
This works on all Pebble watches.<br>

If you do this:<br>
1. Don't ever let the pebble battery run out, you'll have to repeat this pairing<br>
2. Keep bluetooth on your phone turned off, ble connections to the watch while it is also paired to this device via bluetooth cause the app to crash.<br>
   This wasn't a problem a few pebble versions back<br>
3. When and if you turn bluetooth on, your pebble will probably want to upgrade, which is fine.  Turn off the custom device if you're doing this.<br>
   Beware, the pebble upgrade may also blow away the pairing information... That hasn't happened in a while.<br>
4. "This" works for months on end without issue, but, if the device is not longer connecting with the watch, power cycle the device.<br>
    Best bet is to always keep the pebble and the device paired, keep them within a few feet of each other.  I believe that corrupt packets,    due to distance, interference etc. can cause the WT12 to hang.
    

