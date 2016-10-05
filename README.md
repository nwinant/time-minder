Time Minder
===========

_(Name subject to change, because that name seems terrible...)_

A simple, clean, digital watchface for [Pebble](https://www.pebble.com/) which is intended to help the wearer be more aware of the passing of time.

Currently, it offers the following:

* Recurring alerts: vibes at a user-specified interval, with a vibe pattern that's sufficiently aggressive that it's hard to ignore. Can be configured for every hour, every 30 mins, every 20 mins, every 15 mins, every 10 mins, every 5 mins, every 3 mins, or _every minute_ (heavens help you). Default is every 15 minutes.
* Quiet time: configurable start and end time for alerts. Default is 9:00am to 10:00pm.
* Displays time and date.
* Displays minutes remaining until next alert.
* Displays battery % remaining. (Can be hidden.)
* Displays bluetooth connection status. (Can be hidden.) 
* Configurable color scheme.

## Screenshots

### Pebble Time, emulated:

![Watch in Basalt emulator](https://raw.githubusercontent.com/nwinant/time-minder/master/assets/screenshots/basalt.png "Watch in Basalt emulator")
![Watch in Basalt emulator, during quarter-hour alarm](https://raw.githubusercontent.com/nwinant/time-minder/master/assets/screenshots/basalt-alarm.png "Watch in Basalt emulator, during quarter-hour alarm")

### Pebble Round, emulated:

![Watch in Chalk emulator](https://raw.githubusercontent.com/nwinant/time-minder/master/assets/screenshots/chalk.png "Watch in Chalk emulator")
![Watch in Chalk emulator, during quarter-hour alarm](https://raw.githubusercontent.com/nwinant/time-minder/master/assets/screenshots/chalk-alarm.png "Watch in Chalk emulator, during quarter-hour alarm")

### Pebble Classic, emulated:

![Watch in Aplite emulator](https://raw.githubusercontent.com/nwinant/time-minder/master/assets/screenshots/aplite.png "Watch in Aplite emulator")
![Watch in Aplite emulator, during quarter-hour alarm](https://raw.githubusercontent.com/nwinant/time-minder/master/assets/screenshots/aplite-alarm.png "Watch in Aplite emulator, during quarter-hour alarm")



## TODO

* Make alert vibe user-configurable.
* Add vibrate on disconnect.
* Currently vibes on alert minute every time watchface is loaded (i.e., vibes at :15 after; if you click into an app and then go back to the watchface within a minute, it'll vibe again.)
* A bunch of testing, debugging, and combing for memory leaks, probably.
* Release first version to the Pebble app store.
