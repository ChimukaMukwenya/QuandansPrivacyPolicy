# Quandans AI Study Assistant 🎓

An intelligent Flutter-based study companion that helps students with their academic work using AI-powered assistance.

## 📱 Features

- **AI-Powered Study Help**: Get intelligent assistance with your study materials and questions
- **Customizable AI Responses**: Choose from different AI answering styles (Serious, Casual, Mixed, Custom)
- **Personalized Settings**: 
  - Toggle emojis in responses
  - Enable/disable bullet points formatting
  - Encouragement mode for motivation
- **Theme Support**: Light, Dark, and System theme options
- **File Management**: Custom download path selection for saving study materials
- **Cross-Platform**: Built with Flutter for Android, iOS, and desktop platforms

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.0 or higher)
- Dart SDK
- Android Studio / VS Code with Flutter extensions
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/quandans-ai-study-assistant.git
   cd quandans-ai-study-assistant
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

### Building for Release

**Android APK:**
```bash
flutter build apk --release
```

**iOS:**
```bash
flutter build ios --release
```

**Desktop (Windows/macOS/Linux):**
```bash
flutter build windows --release
flutter build macos --release
flutter build linux --release
```

## 🛠️ Dependencies

- `flutter/material.dart` - UI framework
- `file_picker: ^10.1.9` - File and directory selection
- `shared_preferences` - Local data persistence

## 📁 Project Structure

```
lib/
├── main.dart              # App entry point
├── pages/
│   └── settings_page.dart # Settings and preferences UI
├── models/               # Data models
├── services/            # AI and backend services
└── utils/              # Helper functions and constants
```

## ⚙️ Configuration

The app stores user preferences locally using `SharedPreferences`:

- **Theme**: User's preferred app theme
- **AI Style**: Preferred AI response style
- **UI Preferences**: Emoji usage, bullet points, encouragement mode
- **Download Path**: Custom path for file downloads

## 🤖 AI Features

- **Multiple Response Styles**: Adapt AI responses to your preference
- **Context-Aware**: AI understands academic context and provides relevant help
- **Privacy-Focused**: Your study data remains private and secure
- **Customizable**: Tailor the AI assistant to your learning style

## 🔒 Privacy & Security

- **Local Data Storage**: Your preferences are stored locally on your device
- **No Data Sharing**: We don't sell or share your personal study data
- **Encrypted Communication**: All data transmission is encrypted
- **Academic Integrity**: Designed to assist learning, not replace it

For detailed privacy information, see our [Privacy Policy](privacy-policy.html).

## 🎯 Roadmap

- [ ] Voice input support
- [ ] Offline AI capabilities
- [ ] Study progress tracking
- [ ] Collaborative study features
- [ ] Integration with popular learning platforms
- [ ] Advanced note-taking features

## 🐛 Known Issues

- File picker may show warnings on some platforms (resolved in latest versions)
- Theme changes require app restart on some devices

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines

- Follow Flutter/Dart style guidelines
- Write tests for new features
- Update documentation for significant changes
- Ensure compatibility across platforms

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Chimuka Mukwenya**
- Website: [https://chimukamukwenya.github.io/myportifolio](https://chimukamukwenya.github.io/myportifolio)
- Email: cinamtechnologies@gmail.com
- Company: Cinam Technologies

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- The open-source community for various packages used
- Beta testers and early users for their valuable feedback

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/quandans-ai-study-assistant/issues) page
2. Create a new issue with detailed information
3. Contact us at cinamtechnologies@gmail.com

## ⭐ Show Your Support

If this project helped you, please consider giving it a star ⭐ on GitHub!

---

**Made with ❤️ for students worldwide**
