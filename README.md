clear
cd android
./gradlew clean
cd..
clear
yarn install
clear
react-native start
clear
react-native run-android
clear
npm i
clear
npm i @react-navigation/native react-native-gesture-handler react-redux react-native-webview expo-status-bar react-native-maps react-native-geolocation-service react-native-google-places-autocomplete react-native-vector-icons react-native-dropdown-picker @react-navigation/stack @react-navigation/drawer @react-navigation/material-top-tabs @react-navigation/bottom-tabs react-native-paper redux axios react-native-reanimated react-native-screens react-native-safe-area-context react-native-pager-view
clear

babel.config.js =>

module.exports = {
  presets: ['module:metro-react-native-babel-preset'],
  plugins: ['react-native-reanimated/plugin'],
};

apply from: "../../node_modules/react-native-vector-icons/fonts.gradle" // add this line in android/app/build.gradle

npm i @react-native-async-storage/async-storage": "^1.17.11",
npm i react-native-tab-view": "^3.3.4",
npm i @react-native-firebase/app @react-native-firebase/messaging

npm i realm@10.10.1

npm un react-native-firebase
npm un realm
npm un realm@10.10.1
npm un realm@10.24.0

npm link 

Calculator - BUILD SUCCESSFUL
FcmTest - BUILD FAILED
FirebaseDatabaseAuthentication - BUILD FAILED in 21m 33s
FirebaseMessaging - BUILD SUCCESSFUL in 14m 27s
MainProject - BUILD FAILED in 30m 17s
Razorpay - BUILD FAILED
react-native-ui-master - BUILD FAILED
RealmApp - BUILD FAILED in 8m 50s
Redux - BUILD FAILED in 6s
redux functional test task - BUILD FAILED in 10s
TODO - BUILD SUCCESSFUL in 18m 35s

https://react-native-community.github.io/upgrade-helper/?from=0.66.0&to=0.73.2