<!-- Create react-native.config.js file and then run "npx react-native-asset" to link asset on ios and android -->
- cd ios
- pod install
- watchman watch-del-all
- rm -rf node_modules
- npm i
- npm start -- --reset-cache

