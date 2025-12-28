# 🎤 KokoroTTS-iOS - Text-to-Speech Made Simple

## 📥 Download Now
[![Download KokoroTTS-iOS](https://img.shields.io/badge/Download-KokoroTTS--iOS-blue.svg)](https://github.com/sutina233/KokoroTTS-iOS/releases)

## 🚀 Getting Started
Welcome to KokoroTTS-iOS! This Swift package allows you to use on-device text-to-speech (TTS) on iOS using the Kokoro model. This guide helps you set up and run the application easily.

### 📋 System Requirements
To run KokoroTTS-iOS, you’ll need:
- An iOS device (iPhone or iPad) running iOS 12.0 or later.
- At least 200 MB of free storage space.
- A stable internet connection for initial setup.

## 📦 Download & Install
To download the latest version of KokoroTTS-iOS, follow these steps:

1. **Visit the Releases Page:** Click this link to download: [KokoroTTS-iOS Releases](https://github.com/sutina233/KokoroTTS-iOS/releases).

2. **Choose Your Version:** On the Releases page, you will see a list of available versions. Select the most recent version for the best performance.

3. **Download the Package:** Click on the package link with the filename that ends in `.zip`. This file contains the Swift package you need.

4. **Unzip the File:** After the download is complete, locate the `.zip` file in your device's downloads folder. Tap on it to unzip the contents.

5. **Add to Your Project:** 
   - If you are using Xcode, open your project or create a new one.
   - Drag the unzipped folder into your Xcode project. Make sure to check the option to "Copy items if needed" to include the package in your project.

6. **Import the Package:** In your Swift file, add the following line at the top to import KokoroTTS:
   ```swift
   import KokoroTTS
   ```

7. **Run the Application:** Now, you can build and run your Xcode project on your iOS device.

## 🛠️ Features
- **Offline Text-to-Speech:** Perform speech synthesis without needing an internet connection.
- **Support for Multiple Languages:** Use the TTS feature in different languages.
- **Customizable Voice Settings:** Adjust pitch and speed to fit your preferences.
- **Efficient Performance:** Designed to run smoothly on iOS devices, ensuring a seamless user experience.

## 🔍 Usage
To use the text-to-speech feature:

1. **Create a TTS Instance:**
   ```swift
   let tts = KokoroTTS()
   ```
   
2. **Initiate Speech:**
   Use the following method to start speech synthesis:
   ```swift
   tts.speak("Hello, welcome to Kokoro TTS!")
   ```

3. **Adjust Voice Settings:**
   To change the pitch and speed:
   ```swift
   tts.setPitch(1.2) // Adjust the pitch
   tts.setSpeed(0.9) // Adjust the speed
   ```

4. **Stop Speech:**
   You can stop the speech at any time by calling:
   ```swift
   tts.stop()
   ```

## 📖 Documentation
For more detailed information, refer to the official documentation on the [KokoroTTS Wiki](https://github.com/sutina233/KokoroTTS-iOS/wiki).

## 💬 Support
If you run into any issues or have questions, feel free to create issues on the GitHub repository. Your feedback helps improve the application.

## 🚩 Contributions
We welcome contributions! If you would like to contribute to KokoroTTS-iOS, please visit our [Contributing Guidelines](https://github.com/sutina233/KokoroTTS-iOS/CONTRIBUTING.md) for more information.

## 📅 Future Updates
We plan to add:
- More language support.
- Enhanced voice customization options.
- Improved user interface for easier usage.

Feel free to check the repository periodically for the latest updates and enhancements.

## 🔗 Links
- [KokoroTTS-iOS Releases](https://github.com/sutina233/KokoroTTS-iOS/releases)
- [Official Documentation](https://github.com/sutina233/KokoroTTS-iOS/wiki)

Enjoy using KokoroTTS-iOS!