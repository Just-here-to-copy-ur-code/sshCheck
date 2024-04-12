Forked from Raspi Check[![Build Status](https://travis-ci.org/eidottermihi/rpicheck.svg?branch=master)](https://travis-ci.org/eidottermihi/rpicheck)



Android app for checking the status of your computers on the local Network.

The goal of this Fork is to slim down the Raspi Check app and allow it to support other computers.

Like RasPi Check, sshCheck uses a SSH connection (using [SSHJ](https://github.com/hierynomus/sshj)) to connect to your Raspberry Pi ® and queries the information using Linux utilities like `ps`, `df` or the [`/proc` virtual filesystem](https://www.tldp.org/LDP/Linux-Filesystem-Hierarchy/html/proc.html). This app also works on other SBCs via [fake_vcgencmd](https://github.com/clach04/fake_vcgencmd), e.g. when running [Armbian](https://www.armbian.com).


I have literally never programmed an android app. I just wanted to remove some stuff and make it seem better integrated with other computers. 
This fork is mostly supposed to be for perosnal use and I wouldnt be surprised if I end up just hardcoding some stuff.

Copyright Information
------------
The app logo is a derivative of "Raspberry.ico" by [Martina Šmejkalová](http://www.sireasgallery.com/), used under [CC BY](http://creativecommons.org/licenses/by/2.0/). The app logo is licensed under [CC BY](http://creativecommons.org/licenses/by/2.0/) by [Michael Prankl](https://github.com/eidottermihi).

'RasPi' is one of the Rasberry Pi ® abbreviations. For more information visit [http://www.raspberrypi.org](http://www.raspberrypi.org). Raspberry Pi is a trademark of the Raspberry Pi Foundation.
