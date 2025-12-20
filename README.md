![Image](https://github.com/user-attachments/assets/3059d44b-abde-4a16-8afb-dbdeab80728b)

📰 News App - Flutter
A modern, high-performance news application built with Flutter and Dart. The app delivers real-time global news updates with categorized filtering and keyword search functionality, providing a seamless reading experience.

🚀 Features
Real-time News: Fetches the latest global headlines using RESTful APIs.

Category Filtering: Browse news by categories (Business, Technology, Sports, etc.).

Keyword Search: Find specific articles easily with a robust search feature.

Dynamic Theming: Full support for Dark and Light modes.

Responsive UI: Optimized for a smooth experience across various screen sizes.

Seamless Navigation: Fast and intuitive transitions between screens.

🛠️ Tech Stack & Architecture
This project follows the MVVM (Model-View-ViewModel) architectural pattern to ensure clean, maintainable, and scalable code.

Framework: Flutter

State Management: Riverpod (for robust and reactive state handling)

Navigation: AutoRoute (for strongly-typed routing)

Networking: Dio (for handling HTTP requests)

Architecture: MVVM Pattern

UI Components: Material Design

📦 Installation
Clone the repository:

Bash

git clone https://github.com/elsankry02/news_app.git
Navigate to the project directory:

Bash

cd news_app
Install dependencies:

Bash

flutter pub get
Run the app:

Bash

flutter run
📂 Project Structure
Plaintext

lib/
├── data/           # Models and API providers
├── providers/      # Riverpod state providers
├── ui/             # Screens and reusable widgets
├── view_models/    # Logic for UI screens
└── main.dart       # App entry point

