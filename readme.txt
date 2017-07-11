$ node -v
v7.5.0

$ npm -v
5.2.0

$ react-native -v
react-native-cli: 2.0.1
react-native: 0.45.1

--------------------------------------
Usefull commands:

npm install --save react-native@0.45.1

npm install npm@latest -g

npm uninstall react-native-mock

give full permission to the folder

watchman watch-del C:/Intelex/mobilev2/native ; watchman watch-project C:/Intelex/mobilev2/native

react-native start --reset-cache 

watchman watch-del-all
rm -rf node_modules && npm install

rm -fr $TMPDIR/react-*

  or
  
npm start -- --reset-cache

npm cache clean --force

--------------------------------------

https://stackoverflow.com/questions/40519540/how-to-integrate-fcm-firebase-cloud-messaging-with-react-native

http://localhost:8081/index.android.bundle

Make sure your pakage name in mainifests file same as your gradle's applicationId.

https://console.firebase.google.com/project/bob-fcm-push-notification/notification