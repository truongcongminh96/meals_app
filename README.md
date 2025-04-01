
# 🍽️ Flutter Meals App

A simple, beautiful Flutter meals browsing app built as an example to demonstrate state management using **Riverpod**.

## 🎯 Purpose

This project was created to:

- Explore **Riverpod** for efficient and scalable state management
- Practice Flutter app architecture using providers and data models
- Create a functional UI using widgets, lists, and routing
- Implement filtering and favorites functionality in a clean way

## 🧱 Project Structure

```
lib/
├── Data/                   # Dummy data used in the app
├── Models/                 # Data models (e.g. Meal, Category)
├── Providers/              # Riverpod providers (favorites, filters, meals)
├── Screens/                # Screen UI (categories, filters, details, tabs)
├── Widgets/                # Reusable widgets (grid items, drawers, etc.)
└── main.dart               # App entry point
```

## 🧪 Features

- ✅ Browse meals by category
- ✅ Filter meals by dietary preferences (gluten-free, vegetarian, vegan, lactose-free)
- ✅ Mark meals as favorites
- ✅ View detailed meal steps and ingredients
- ✅ State management handled using **Riverpod**
- ✅ Clean folder structure following best practices

## 🛠️ Technologies Used

- ✅ Flutter (3.29 stable)
- ✅ Dart
- ✅ Riverpod (hooks_riverpod or flutter_riverpod)
- ✅ VS Code or Android Studio

## 🚀 Getting Started

```bash
flutter pub get
flutter run
```

## 📸 Screenshots

> (Add UI screenshots here if needed)

## 📦 Suggestions for Improvement

- Add persistent storage using `shared_preferences` or `hive`
- Add dark/light theme switch with Riverpod
- Add unit and widget tests using `flutter_test`

## 👨‍💻 Author

- Name: **Truong Cong Minh**
- Purpose: Built as an educational example to showcase Flutter + Riverpod in practice.

## 📄 License

This project is licensed under the MIT License.
