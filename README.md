# 🏋️ Daily Fitness App in React Native

### Welcome! 👋

## 📜 Table of Contents

- [🌟 Overview](#-overview)
  - [🔥 The Challenge](#-the-challenge)
  - [🛠️ How to Setup The Project](#-how-to-setup-the-project)
  - [🎥 Demo Screenshot](#-demo-screenshot)
  - [🔗 Links](#-links)
- [🚀 How to Run](#-how-to-run)
- [🔨 How to Build](#-how-to-build)
- [👀 How to Preview the Build](#-how-to-preview-the-build)
- [🌐 How to Host](#-how-to-host)
- [🛠️ My Process](#-my-process)
  - [🧰 Built With](#-built-with)
  - [💡 What I Learned](#-what-i-learned)
  - [🚀 Continued Development](#-continued-development)
  - [📚 Useful Resources](#-useful-resources)
- [🏁 Get Started](#-get-started)
  - [🏃🏻‍➡️ Run the App](#-run-the-app)
- [✍️ Author](#-author)
- [🙏 Acknowledgments](#-acknowledgments)

## 🌟 Overview

### 🔥 The Challenge

Users should be able to:

- 📊 Track daily fitness activities and goals  
- 🎥 View detailed exercise routines with animations  
- 🌍 Access a variety of workouts fetched from Rapid API  
- 💾 Cache data for offline access  
- ✨ Experience a responsive and smooth user interface  

### 🛠️ How to Setup the Project

To set up the project locally, follow these steps:

1. Clone the repository using GitHub Desktop or Git Bash:  
   ```bash
   git clone https://github.com/SartHak-0-Sach/Daily_fitness_app_ReactNative.git
   ```

2. Navigate to the project directory:  
   ```bash
   cd Daily_fitness_app_ReactNative
   ```

3. Install the necessary dependencies:  
   ```bash
   npm install
   ```

### 🎥 Demo Screenshot

![React Native Fitness App Demo](./readme-images/React-Native-Fitness-App.png "Desktop Demo")

### 🔗 Links

Here are some helpful documentation references:  

- 📖 [React Native Official Documentation](https://reactnative.dev/docs/getting-started)  
- 🧭 [Expo Router Guide](https://expo.dev/router)  
- 🎨 [Tailwind CSS Documentation](https://tailwindcss.com/docs)  
- 🌀 [Reanimated Docs](https://docs.swmansion.com/react-native-reanimated/)  
- 🌍 [Rapid API Documentation](https://rapidapi.com/docs/)

## 🚀 How to Run

```bash
npm start
```

Use the [Expo Go](https://expo.dev/) app to scan the QR code and run the app on your mobile device.

## 🔨 How to Build

```bash
npm run build
```

A `dist` folder should be created.

## 👀 How to Preview the Build

```bash
npm run preview
```

## 🌐 How to Host

### How to Deploy the Project

To host the **Daily Fitness App** built with React Native, follow these steps:

1. **Create a Build for Production:**
   Use Expo to generate production-ready builds for Android or iOS:  
   ```bash
   expo build:android
   ```  
   or  
   ```bash
   expo build:ios
   ```

2. **Sign the Build (if required):**
   - For Android, download the `.apk` file for testing or distribute it via Google Play.
   - For iOS, follow the App Store guidelines to upload and sign your `.ipa` file.

3. **Host a Web Version (Optional):**
   - Run the following command to build the app for web:  
     ```bash
     expo build:web
     ```  
   - Upload the `web-build` folder to a hosting provider like [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/).

4. **Hosting Back-End (if applicable):**
   - If your app depends on back-end APIs, ensure the API endpoints are hosted using services like [Heroku](https://www.heroku.com/), [AWS](https://aws.amazon.com/), or [Render](https://render.com/).

5. **Environment Variables:**
   - Make sure to securely store API keys (e.g., for Rapid API) in `.env` files and use services like **Expo Secrets** or **AWS Secrets Manager**.

For detailed deployment guides, refer to the following resources:  
- [Expo Deployment Docs](https://docs.expo.dev/distribution/introduction/)

## 🛠️ My Process

### 🧰 Built With  

| **Technology**      | **Description**                                     |
|----------------------|-----------------------------------------------------|
| ⚛️ **React Native** | Framework for cross-platform mobile app development |
| 🧭 **Expo Router**  | Navigation library for Expo apps                    |
| 🎨 **TailwindCSS**  | Utility-first CSS framework for styling             |
| 🌀 **Reanimated**   | Library for animations in React Native              |
| 🌍 **Rapid API**    | Platform for accessing external APIs                |
| 💾 **Caching**      | Data caching techniques for offline access          |

### 💡 What I Learned

Working on this project allowed me to:  

- Dive deep into mobile app development using **React Native** and **Expo**.  
- Integrate animations using **Reanimated**.  
- Fetch data dynamically using **Rapid API** and manage data efficiently with caching techniques.

### 🚀 Continued Development

Future improvements:  

- 🔒 Adding user authentication  
- 📝 Personalized workout plans  
- 📈 Real-time progress tracking  
- 🎥 Enhanced animations for better UX  

### 📚 Useful Resources

- [React Native Documentation](https://reactnative.dev/docs/getting-started)  
- [Expo Documentation](https://docs.expo.dev/)  
- [TailwindCSS Documentation](https://tailwindcss.com/docs)  
- [Reanimated Documentation](https://docs.swmansion.com/react-native-reanimated/)  
- [Rapid API Documentation](https://rapidapi.com/docs/)  

## 🏁 Get Started

Install development dependencies:

```bash
npm install
```

### 🏃🏻‍➡️ Run the App

#### 🚀 Start in Development Mode:
```bash
npm start
```

Use the [Expo Go](https://expo.io) app on your phone to view it. Edits to your files will reload automatically.

#### 📱 Run on iOS:
```bash
npm run ios
```
This will open the app in the iOS Simulator (Mac only).

#### 🤖 Run on Android:
```bash
npm run android
```
Open the app on a connected Android device or emulator. Ensure Android build tools are installed ([React Native docs](https://facebook.github.io/react-native/docs/getting-started.html)).

## ✍️ Author

**Sarthak Sachdev**  
- 🌐 Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)  
- 💻 LeetCode - [@sarthak_sachdev](https://leetcode.com/u/sarthak_sachdev/)  
- 🐦 Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)  

## 🙏 Acknowledgments

Special thanks to:  
- 🎥 YouTube tutorials  
- 🧑‍💻 Stack Overflow  
- 📜 Various tech blogs  

These resources provided invaluable guidance during development.

## 💬 Got Feedback?

I love receiving feedback! Feel free to reach out to me at **saarsaach30[at]gmail[dot]com**.  

If you enjoyed the project, don't forget to share it!  

**Happy coding!** 🚀🎉
