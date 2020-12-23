# Generalised-AR-Modelling
## Steps to run:-
1. Install Node Modules
`npm install`
2. Turn on USB Debugging on the device and connect your device with a USB Cable to the system.
3. Run `adb devices` to check if your device is listed.
4. Run `adb reverse tcp:8081 tcp:8081`
5. Start the Metro Bundler `npm start -- --reset-cache`
6. Open the **android** folder in Android Studio.
7. Run the project by clicking the ▶ (Run) in Android Studio.  

Ta-Da! You will see the AR app running on your device.
