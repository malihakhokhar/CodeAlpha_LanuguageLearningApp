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

<img width="1080" height="2280" alt="Screenshot_1755354786" src="https://github.com/user-attachments/assets/f15ca59d-5f5c-4b99-a1e0-b049a2a09680" />
<img width="1080" height="2280" alt="Screenshot_1755354783" src="https://github.com/user-attachments/assets/68eab971-57ce-4cea-8c7e-840cd62cc850" />
<img width="1080" height="2280" alt="Screenshot_1755354777" src="https://github.com/user-attachments/assets/f0bfc675-ad13-49cf-a4b0-37741ce94e83" />
<img width="1080" height="2280" alt="Screenshot_1755354772" src="https://github.com/user-attachments/assets/7cff23d2-08c4-4da6-9968-61cfc1aa1d1e" />
<img width="1080" height="2280" alt="Screenshot_1755354755" src="https://github.com/user-attachments/assets/8fa5d8c2-2aba-4a5f-9231-35fb6425a05a" />
<img width="1080" height="2280" alt="Screenshot_1755354752" src="https://github.com/user-attachments/assets/961f114b-b53f-4242-8382-de52ab5d7fd2" />
<img width="1080" height="2280" alt="Screenshot_1755354748" src="https://github.com/user-attachments/assets/0f4449f6-5e01-4eac-8a9d-5040c0a0aaa1" />
<img width="1080" height="2280" alt="Screenshot_1755354796" src="https://github.com/user-attachments/assets/d83586d1-49a0-4e65-81eb-b60e9d9db0c4" />

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
