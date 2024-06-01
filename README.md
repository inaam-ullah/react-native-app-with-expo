# React Native app with Expo 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

## How to create a new React Native App with Expo

Follow the steps below to set up and run the project:

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm or yarn
- Expo CLI

**Note:- You can use brew to install.**

### Installation

1. Install Expo-cli if you have not already

   ```bash
   npm install -g expo-cli
   ```

2. Create a new project with default template.(You can choose your own template whatever you want by go into the expo [website](https://docs.expo.dev/more/create-expo/#--template) and explore more.)

   ````bash
   npx create-expo-app@latest  --template default
   ````

3. Configure EAS Build

   Navigate to your project directory and run the following command to create an EAS config in your project:

   ```bash
   eas build:configure
   ```

### Running the Project:

1. Start the Expo App

   ```bash
   npx expo start
   ```

2. Remove Bioplerplate code

   ```bash
   npm run reset-project
   ```

3. Generates native Android and iOS directories using Prebuild.

   ```bash
   npx expo prebuild
   ```

### Running on Different Platforms

To run your project on different platforms, navigate to the directory and run one of the following npm commands.

1. Navigate to your project directory

   ```bash
   cd reactive-native-app-with-expo
   ```

2. Run on Android

   ```bash
   npm run android
   ```

3. Run on iOS

   ```bash
   npm run ios
   ```

4. Run on Web

   ```bash
   npm run web
   ```

### Project Structure

**src:** Contains the main application code.

**assets:** Contains image and other asset files.

**node_modules:** Contains all the npm packages.

**android:** Contains the native Android project files.

**ios:** Contains the native iOS project files.

Hurray!!! your new project is ready.

Happy coding!
