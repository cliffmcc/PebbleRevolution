## Revolution watchface

![Photo](http://d.pr/i/Qe9k+)

[Video of time animation](http://d.pr/v/nQWY)

Implemented by Douwe Maan.

BlueTooth additions by Cliff McCollum.

Envisioned as a watchface by Jean-Noël Mattern (Jnm), who posted it in the ["Watch-face ideas" thread](http://forums.getpebble.com/discussion/comment/3538/#Comment_3538) on the Pebble forums.

Based on the display of the [Freebox Revolution](http://www.free.fr/adsl/freebox-revolution.html), which was designed by Philippe Starck.

This version of the Revolution watchface vibrates whenever your Bluetooth signal is lost. No longer worry about leaving your phone somewhere by accident - your Pebble will vibrate every 15-seconds if it loses connection with your phone. As soon as the Bluetooth connection returns, the vibrating will stop.

####How It Works
* Every time the BlueTooth signal is lost or restored, your Pebble will make two quick vibrations letting you know something has changed.
* If the signal has been lost, your Pebble will vibration rapidly every 15 seconds until the signal is restored.
* If you want to silence the vibrations on purpose (for example, while you are locating your phone or if you disable Bluetooth on an airplane) just switch to a different Watchface.

### Download version 2.0.1

* [RevolutionBT.pbw](https://github.com/cliffmcc/PebbleRevolution/blob/master/releases/RevolutionBT.pbw)
* [RevolutionBT-VibeOnHour.pbw](https://github.com/cliffmcc/PebbleRevolution/blob/master/releases/RevolutionBT-VibeOnHour.pbw) (vibrates on the hour)

#### American (date formatted as MM-DD)
* [RevolutionBT-American.pbw](https://github.com/cliffmcc/PebbleRevolution/blob/master/releases/RevolutionBT-American.pbw)
* [RevolutionBT-American-VibeOnHour.pbw](https://github.com/cliffmcc/PebbleRevolution/blob/master/releases/RevolutionBT-American-VibeOnHour.pbw) (vibrates on the hour)

## License
Original code Copyright (c) 2013 [Douwe Maan](http://www.douwemaan.com/)

BlueTooth additions Copyright (c) 2014 Cliff McCollum

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.