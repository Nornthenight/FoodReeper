# FoodReeper
A food storage management app to track ingredients, monitor expiration dates, and manage your pantry efficiently

## Features

- 📱 Track food items and their expiration dates
- 🗂️ Organize items by category and storage location
- ⏰ Get reminders for expiring items
- 📊 Manage inventory with detailed statistics
- 🔍 Search and filter items quickly
- 💾 Local database storage with Room
- 🎨 Clean and intuitive Material Design UI

## Tech Stack

- **Language**: Kotlin
- **UI Framework**: Android Jetpack (AppCompat, ConstraintLayout)
- **Database**: Room ORM
- **Architecture**: MVVM with LiveData
- **Build Tool**: Gradle
- **Target API**: Android 34 (API 34)
- **Min SDK**: Android 7.0 (API 24)

## Project Structure

```
FoodReeper/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── kotlin/
│   │   │   │   └── com/foodreeper/
│   │   │   │       ├── ui/
│   │   │   │       │   └── MainActivity.kt
│   │   │   │       ├── data/
│   │   │   │       │   └── Food.kt (Model)
│   │   │   │       └── database/
│   │   │   │           └── FoodDatabase.kt
│   │   │   └── AndroidManifest.xml
│   ├── build.gradle (App-level configuration)
│   └── proguard-rules.pro
├── build.gradle (Project-level configuration)
├── .gitignore
└── README.md
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Nornthenight/FoodReeper.git
cd FoodReeper
```

2. Open the project in Android Studio

3. Build and run:
```bash
./gradlew build
./gradlew installDebug
```

## Dependencies

- AndroidX AppCompat
- Android Material Design
- Room Database
- Lifecycle ViewModel
- Fragment KTX
- Kotlin Coroutines

## Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- JDK 8 or higher
- Gradle 7.0 or later

### Building
1. Open project in Android Studio
2. Sync Gradle files
3. Build the project
4. Run on emulator or physical device

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Author

Nornthenight

## Support

For issues and questions, please open an issue on GitHub.
