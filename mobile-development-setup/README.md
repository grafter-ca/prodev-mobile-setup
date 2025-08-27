# Expo Go Installation and Setup

## Steps to Install Expo Go

1. **Visit the official Expo Go homepage**  
   [https://expo.dev/go](https://expo.dev/go)

2. **Select the latest SDK version**  
   - Ensure compatibility with your project.

3. **Install Expo Go for your device**
   - **Android**: [Download from Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)  
   - **iOS**: [Download from Apple App Store](https://apps.apple.com/app/expo-go/id982107779)

4. **Open the Expo Go app**  
   - Launch the application after installation.

5. **Create an account or log in**  
   - New users: Sign up for a free Expo account.  
   - Existing users: Log in with your credentials.

---

## Challenges Faced
- **Signup issue:** The app didn’t let me complete the signup process on the first attempt.  
- **Fix:** Restarted the app and ensured stable internet connection before trying again.  

---

## Notes
- Expo Go allows you to run React Native apps directly on your device without building them natively.  
- Make sure you have the same SDK version installed locally when developing with Expo.  
- If using `npx create-expo-app`, ensure it matches the Expo Go SDK to avoid runtime errors.

---

## Next Steps
- Install Node.js and `npm` (or `yarn`) to create and manage Expo projects.  
- Run the following to create a new project:  
  ```bash
  npx create-expo-app my-app
  cd my-app
  npx expo start
