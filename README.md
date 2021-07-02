# pinetime-infinitime-time-synchronization

Sync the time on your PineTime using Chrome over Bluetooth LE

I have successfully used this on Pop!_OS/Ubuntu 20.04 LTS, using the Edimax BT-8500 USB adapter (I compiled the kernel module from their website).

## Instructions

1. Open index.html in Chrome
1. Open chrome://flags in a new tab
1. Enable "Experimental Web Platform features" to activate Bluetooth API functionality. You may need to restart Chrome
1. Make sure your PineTime is on and the display is on
1. Press the Sync button on the webpage
1. A dialog will pop up, after 5 seconds you should see your InfiniTime device appear. You may need to restart your PineTime if you don't see it
1. Select your device and click Pair
1. After about 10 seconds the time should be synced ... check your PineTime!