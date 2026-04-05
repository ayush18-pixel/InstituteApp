# UhlLink (InstituteApp)

![Flutter Version](https://img.shields.io/badge/Flutter-%5E3.5.0-blue.svg?logo=flutter)
![Dart Version](https://img.shields.io/badge/Dart-%5E3.5.4-blue.svg?logo=dart)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)

**UhlLink** is a comprehensive, centralized Flutter application designed to simplify campus life for students and staff. Modeled to act as a unified hub, it bridges the gap between academics, campus resources, and student interaction by providing secure authentication, a peer-to-peer marketplace, lost and found services, a job portal, and a live feed for campus activities.

## 🌟 Why UhlLink?

UhlLink empowers the campus community by bringing essential services into a single, cohesive platform. It solves the everyday problems students face and ensures important updates and opportunities are easily accessible.

### Key Features
- 🔐 **Secure Authentication**: Robust user authentication system handling Sign Ups, Logins, OTP verifications, and Password management. 
- 📢 **Campus Feed**: An interactive, real-time feed for sharing important institute-wide updates, announcements, and events.
- 🎒 **Lost & Found Portal**: Easily report lost items or browse found items to reunite students with their belongings.
- 🛒 **Buy & Sell Marketplace**: A dedicated, peer-to-peer marketplace where students can list books, electronics, and accessories.
- 💼 **Job & Internship Portal**: A centralized hub for accessing campus placements, internships, and career opportunities.
- 🔔 **Instant Notifications**: Keep users informed with real-time alerts.
- 🍽️ **Cafeteria Integration**: Includes cafeteria resources designed to help students track and browse campus dining options.

## 🚀 Getting Started

Follow these instructions to set up the project locally on your machine for development and testing purposes.

### Prerequisites

You need the following installed on your system:
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (version `^3.5.0`)
- [Dart SDK](https://dart.dev/get-dart)
- A working instance of MongoDB (Local or Atlas)
- Android Studio / VS Code with the Flutter extension

### Installation & Setup

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/your-username/instituteapp.git
   cd instituteapp
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Environment Setup**:
   The application uses environment variables for secure database connections. 
   Create a file named `institute.env` in the root directory of your project and populate it with your MongoDB connection string:
   ```env
   DB_CONNECTION_URL="mongodb+srv://<username>:<password>@cluster.mongodb.net/<database>?retryWrites=true&w=majority"
   ```
   *(Note: Ensure `institute.env` is added to your `.gitignore` to prevent sensitive data exposure).*

4. **Run the App**:
   Select your target device (Emulator or Physical device) and run:
   ```bash
   flutter run
   ```

## 📚 Usage Examples

Once installed, here is how you can perform some basic actions:
- **Sign In**: Open the app, navigate to the authentication screen, and use your registered campus email and password.
- **Posting an Item for Sale**: Head over to the `Buy & Sell` section from the dashboard, click the '+' icon, upload image assets, set a price, and publish your listing.
- **Checking Notifications**: Tap the bell icon in the top right corner of the home screen to view your latest alerts and academic updates.

## 🆘 Support and Help

Having trouble with your development setup or looking for technical documentation?
- Refer to the official [Flutter Documentation](https://docs.flutter.dev/) to learn more about the framework.
- Explore [Bloc state management documentation](https://bloclibrary.dev/) which is heavily utilized in this application.
- If you encounter a bug or have a feature request, please [Open an Issue](../../issues) in this repository.

## 🤝 Maintainers and Contributing

We welcome contributions from the community to improve UhlLink! 

**Maintainers**:
- Core Development Team ([@ayush18-pixel](https://github.com/ayush18-pixel))+ IIT Mandi Winter Project Team

**How to Contribute**:
1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

For detailed instructions, please check our [Contributing Guidelines](docs/CONTRIBUTING.md) (coming soon!).
