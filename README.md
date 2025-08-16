# 🌍 Code Alpha_Language Learning App (Android - Kotlin)

A clean and user-friendly Android app built in **Kotlin** that helps users learn new languages through **daily lessons, flashcards, quizzes, and vocabulary practice**.  
The app uses **SQLite (Room Database)** for local data storage and **Firebase Authentication** for signup/login.  
It follows the **MVVM architecture** and integrates Jetpack components for a scalable and maintainable design.

---

## 🚀 Features
- 🔑 **User Authentication**: Sign up & log in securely with Firebase  
- 📚 **Daily Lessons**: Learn new vocabulary and grammar each day  
- 🃏 **Flashcards**: Word with translation and pronunciation  
- 📝 **Quizzes**: Test your knowledge with multiple-choice quizzes  
- 📊 **Progress Tracking**: View your learning history and performance  
- 💾 **Offline Storage**: Vocabulary and lessons stored locally in SQLite (Room)  

---

## 📱 Screenshots  
*(Add your screenshots here)*  
`1` | `2` | `3`

---

## 🛠️ Tech Stack
- **Language**: Kotlin  
- **Architecture**: MVVM  
- **Local Database**: Room (SQLite)  
- **Authentication**: Firebase Auth  
- **UI Components**: RecyclerView, ViewPager2, Material Components, etc.  
- **Jetpack Components**: ViewModel, LiveData, Data Binding, Lifecycle  

---

## 🏛️ Database Overview
- **Entity**: Represents `UserProfile`, `VocabularyItem`, `Lesson`, and `QuizQuestion`  
- **DAO (Data Access Object)**: Provides methods to insert, update, delete, and query data  
- **Database**: Room Database acts as an abstraction over SQLite and provides DAO access  

---

## 📁 Folder Structure
LanguageLearningApp/
├── data/
│ ├── UserProfile.kt
│ ├── VocabularyItem.kt
│ ├── Lesson.kt
│ └── QuizQuestion.kt
│
├── database/
│ ├── AppDatabase.kt
│ └── DaoInterfaces.kt
│
├── repository/
│ └── UserProfileRepository.kt
│
├── ui/
│ ├── fragments/
│ │ ├── GrammarFragment.kt
│ │ ├── DashboardFragment.kt
│ │ ├── VocabularyFragment.kt
│ │ ├── QuizFragment.kt
│ │ └── ProfileFragment.kt
│ ├── activities/
│ │ └── MainActivity.kt
| | └── SignupActivity.kt
| | └── LoginActivity.kt
| | └── selectLanguage.kt
│ └── adapter/
│ └── VocabularyAdapter.kt
│ └── GrammarAdapter.kt
├── viewmodel/
│ └── UserProfileViewModel.kt
│
├── res/
│ └── layout/
│
└── AndroidManifest.xml

-----

## 🔧 Setup Instructions
1. Clone the repository  
   ```bash
   git clone https://github.com/malihakhokhar/CodeAlpha_LanguageLearningApp.git

-------

✅ Requirements
- Android Studio Hedgehog or later
- Kotlin 1.8+
- Gradle 8.0+
- Minimum SDK: 23 (Android 6.0)

---

💡 Future Enhancements
🌐 Multi-language support (Spanish, French, Chinese, etc.)
🔊 Speech recognition for pronunciation practice
☁️ Cloud sync of vocabulary progress with Firebase Firestore
🏆 Gamification (XP points, badges, leaderboard)
🕶️ Dark mode support

-----

📄 License
This project is open-source and available under the MIT License.

------

🙌 Acknowledgements

Android Developers – Jetpack & Room
Firebase Authentication
Kotlin Programming Language
Code Alpha Internship
