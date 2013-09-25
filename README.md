Artoo + Digispark = Fun
=======================

Messing around with the Digispark I got from GoGaRuCo.  
Created this repo as info for anyone else who might also be experimenting with it.


Stuff I've done so far
----------------------
- Assembled my device (noob soldering, yay!)
- Install littlewire onto digispark with 'rvmsudo artoo install digispark'

If you get the error ```LIBUSB::ERROR_ACCESS in libusb_open```, it is because there is a permissions problem accessing the device over USB.
To fix this, prefix the command with 'rvmsudo' rather than calling the artoo gem directly.
