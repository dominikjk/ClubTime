# ClubTime

A gym membership app built in React Native (Expo) with a small team, for my final-year dissertation project in Computer Science at the University of Kent. The project was awarded a First.

The idea was an app that does more than class booking: members can book classes, check in with a QR code, follow workout plans, track nutrition and see a leaderboard, all backed by Firebase.

## My contributions

The screens I wrote are collected in [`MyContributions/`](MyContributions):

- **Class booking** (`BookingPage.js`): pick a date and class, then save the booking to Firestore
- **Booking calendar** (`NewCalendar.js`): see your booked classes by date, using react-native-calendars and Firestore queries
- **QR check-in** (`CheckIn.js`): generates the member's QR code for checking in at the gym
- **Gym map** (`MapPage.js`): shows the gym on a Google map with the user's current location (react-native-maps, expo-location)
- **Account page** (`Accountpage.js`): view and update account details and subscription, or delete the account (Firebase Auth and Firestore)
- **Password reset** (`ForgotPassword.js`)

## Tech

React Native, Expo, Firebase Authentication, Cloud Firestore, React Navigation, react-native-maps, expo-location, react-native-calendars

## Status

This was a university project and isn't maintained. The Firebase config file isn't included, so the app needs your own Firebase project to run.
