#### Create project

`react-native init app-name`

#### Run app on Android

1. Start `android avd`
2. Run `react-native run-android` in the project folder

* Once the app is started, it can be reloaded without building again: hit press R twice to refresh the app.

#### Remote JS debugging

Android: cmd + M
iOS: cmd + D

#### TroubleShooting

* If Android emulator says some `Unknown module` issue, run `npm cache clean` and `npm install`.
* If the Remote JS debugging is turned on, it can make syntax errors find harder. If there are some Java error there, turn of the Remote JS debugging to see if there is a syntax error. (It will show the strace on the screen).
