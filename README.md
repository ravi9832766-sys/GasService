# Gas Services Android App

This is an Android Studio project that wraps the supplied Gas Services dashboard in an Android WebView, preserving the HTML/CSS/JavaScript interface and its splash screen, header, service tiles, forms, support page, and demo payment flow.

## Open in Android Studio
1. Extract `GasServicesAndroid.zip`.
2. In Android Studio choose **Open** and select the extracted `GasServicesAndroid` folder.
3. Allow Gradle sync to finish.
4. Run the `app` configuration on an emulator or Android phone.

## Important
- The payment screen is a **demo only**. The existing page simulates a failed payment and does not collect money.
- No real application submission, backend, database, or payment gateway is connected.
- For production, connect a trusted backend and an authorized payment gateway. Never collect UPI PIN or OTP inside this app.
